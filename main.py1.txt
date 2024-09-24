import streamlit as st


st.title("Welcome to anusha's website")
#st.header("python")
name = st.text_input("What is your name?")
roll_no = st.text_input("What is your roll no?")
clg = st.text_input("What is your clg?")
percentage = st.text_input("What is your percentage?")
address = st.text_area("Enter your Text")
section = st.selectbox("Enter your class :",("A","B","C","D"))
gender = st.selectbox("Enter your Gender",("Male","Female"))
age = st.text_input("Enter your Age")
button = st.button("Done")
if button :
    st.markdown(f"""
    Name : {name}
    Roll No : {roll_no}
    clg : {clg}
    Percentage : {percentage}
    Address : {address}
    section : {section}
    Gender : {gender}
    age : {age}""")





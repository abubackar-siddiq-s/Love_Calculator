import random
import streamlit as st

st.title("Love Percentage Calculator ❤️")

user_name = st.text_input("Enter Your Name:")
lover_name = st.text_input("Enter Your Lover's Name:")

if st.button("Calculate Love"):
    if user_name == "" or lover_name == "":
        st.error("Please enter both names!")
    else:
        love_percentage = random.randint(1, 100)
        
        if love_percentage <= 10:
            love_result = "Low"
        elif 10 < love_percentage <= 40:
            love_result = "Good"
        elif 40 < love_percentage <= 70:
            love_result = "Crazy"
        else:
            love_result = "On Peak"
        
        st.subheader(f"{user_name} ❤ {lover_name}")
        st.write(f"Your Love: {love_percentage}%")
        st.success(f"Your love is {love_result}!")

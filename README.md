import pandas as pd

students_data = {
    "Name": ["John" , "Jacob" , "Emily", "Vector" , "Micheal"],
    "Age": [11,19,21,38,12],
    "Sex": ["Male" , "Male" , "Female" , "Male" , "Male"],
    "live": ["New york" , "San francisco" , "New york" , "chicago" , "arizona"],
}

SD = pd.DataFrame(students_data)

print(SD)

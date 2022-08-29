import pandas as pd
data_dict = {'CustomerID': [1, 2, 3, 4, 5, 6, 7, 8, 9, 10],
              
             'Gender': ["Male", "Female", "Female", "Male",
                        "Male", "Female", "Male", "Male",
                        "Female", "Male"],
              
             'Age': [20, 21, 19, 18, 25, 26, 32, 41, 20, 19],
              
             'Annual Income(k$)': [10, 20, 30, 10, 25, 60, 70,
                                   15, 21, 22],
              
             'Spending Score': [30, 50, 48, 84, 90, 65, 32, 46,
                                12, 56]}
 
data = pd.DataFrame(data_dict)
 
data.to_csv("Customers.csv")
 
print(data)


import pandas as pd
data_dict1 = {'CustomerID': [1, 2, 3, 4, 5, 6, 7, 8, 9, 10],
              
             'Gender': ["Male", "Female", "Female", "Male",
                        "Male", "Female", "Male", "Male",
                        "Female", "Male"],
              
             'Age': [20, 21, 19, 18, 25, 26, 32, 41, 20, 19],
              
             'Annual Income(k$)': [10, 20, 30, 10, 25, 60, 70,
                                   15, 21, 22],
              
             'Spending Score': [30, 50, 48, 84, 90, 65, 32, 46,
                                12, 56]}
 
data1 = pd.DataFrame(data_dict1)
 
data1.to_csv("Customers1.csv")
 
print(data1)

data_dict2 = {'CustomerID': [11, 12, 13, 14, 15, 16, 17, 18, 19, 20],
              
             'Gender': ["Male", "Female", "Female", "Male",
                        "Male", "Female", "Male", "Male",
                        "Female", "Male"],
              
             'Age': [23, 33, 19, 18, 25, 26, 32, 41, 20, 19],
              
             'Annual Income(k$)': [10, 20, 30, 10, 25, 60, 70,
                                   15, 21, 22],
              
             'Spending Score': [38, 59, 48, 99, 94, 66, 44, 51,
                                12, 56]}
 
data2 = pd.DataFrame(data_dict2)
 
data2.to_csv("Customers2.csv")
 
print(data2)

df = pd.concat(
    map(pd.read_csv, ['Customers1.csv', 'Customers2.csv']), ignore_index=True)
print(df)

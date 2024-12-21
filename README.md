# **`Tái hiện conflict`**
git checkout -b branch1 </br>
git add sample.txt</br>
git commit -m"Update sample.txt in branch1"</br>
git checkout develop</br>
git git checkout -b branch2</br>
git add sample.txt</br>
git commit -m"Update sample.txt in branch2"</br>
git checkout develop </br>
git merge branch1</br>
git merge branch2</br>
# **`Conflict`**
![image](https://github.com/user-attachments/assets/600cd107-e3bd-44c4-a17f-ec8265cef680)

# **`Giải quyết conflict trong VScode bằng cách nhấn "Accept Both Changes"`**
![Screenshot from 2024-12-20 23-17-14](https://github.com/user-attachments/assets/98138c7c-89c8-4de9-8eaa-990d84f15d7d)

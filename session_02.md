https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
Write code to check whether a given string is panlindrome or not==>HW
https://git-scm.com/downloads/win
https://code.visualstudio.com/docs/?dv=win64user
https://www.python.org/downloads/
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

x = [2,4,7,8,9,2,8,2]
print(x)
y=sorted(x)
print(y)
z=len(x)
print(z)
if(z%2 == 1):
    m=y[int((z+1)/2)-1]
else:
    m=y[((int(z)/2)-((int(z)/2)+1))/2]
print(m)

# Walkthroughs
1. [Google Colab](https://colab.research.google.com/)

# Installations

1. [Python download link](https://www.python.org/downloads/)
2. [Visual Studio download link](https://code.visualstudio.com/download)
3. [Git bash installation link](https://git-scm.com/downloads) (Mac and Linux users can skip this step)
4. Visual Studio Code Extensions:
    - Jupyter (Microsoft)
    - Andromeda (Eliver Lara)
    - Black Formatter (Microsoft)
    - Flake8 (Microsoft)

## Checklist
1. Git bash terminal access in VS Code
2. Venv creation. 
```bash 
pip install jupyter
```
3. Jupyter notebook
```bash
jupyter notebook
```
4. Auto code correction

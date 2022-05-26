# ESP-IDF Installation in VS Code (Windows)

## Installation Prerequisites

The minimum requirements for running ESP-IDF in VS Code are below.

* **Python**: Download and install Python from [here](https://www.python.org/).
* **Git**: Download and install Git from [here](https://git-scm.com/).
* **VS Code**: Download and install VS Code from [here](https://code.visualstudio.com/).

> Note 1: Make sure Python and Git are available on the system environment path.
>
> Note 2: Upgrade the pip version to the latest by inputting the command `python.exe. -m pip install --upgrade pip` in the command window.

## Installing ESP-IDF

1. Open the **Extensions** view by clicking on the Extension icon in the Activity Bar on the side of VS Code.                  

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729016.png)



2.  Search the extension with ```Espressif IDF```.

  ![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729017.png)



3. Install the extension.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729018.png)



4. Select **View** and **Command Palette**, and type ```ESP-IDF: Configure ESP-IDF extension```.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729019.png)

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729020.png)



5. Now the setup wizard window will be shown with two setup options: **Express** and **Advanced**.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729021.png)



6. Choose **Express** for the fastest option. Make sure that ```IDF_PATH``` and ```IDF_TOOLS_PATH``` do not have any spaces to avoid build issues.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729022.png)



7. You will see a page showing the setup progress status, including **ESP-IDF** download progress, **ESP-IDF Tools** download progress and the creation of a **Python virtual environment**.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729023.png)



8. If everything is installed correctly, you will see a message that **All settings have been configured**.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729024.png)



9. Now that the extension setup is done.

## Common Errors

During creating Python virtual environment, if the **pip version** is not upgraded, there will be a warning ```WARNING: You are using pip version 20.3.3; however, version 22.1 is available```, and the setup fails.

1. Input the command ```python.exe -m pip install --upgrade pip``` in the command window.

![](https://raw.githubusercontent.com/BernadetteZhang/ImagesforMarkdown/main/202205251729025.png)



2. Delete the two folders for installing **ESP-IDF** and **ESP-IDF Tools** in above **step 6** to re-install ESP-IDF.

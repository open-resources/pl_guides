# Preparation

Before you get started with authoring your first question, it's worth getting organized and setting up your working environment so that you can work efficiently, reliably, and reproducibly.

## Questions to consider before starting

Here are some questions you should answer in this section:

1. **What is the path of the directory you want to work in?** Below are some **suggestions** but select a path that makes sense to you. The examples below assume your computer username is `pixiedust`:
    - On macOS:
        - `/Users/pixiedust/Documents/Summer2023/`
        - `/Users/pixiedust/Desktop/Summer2023/`
        - `/Users/pixiedust/Documents/`
        - `/Users/pixiedust/`

    ```{warning}
    It is not recommended that you clone repositories in cloud-hosted folders (such as Dropbox, Box.com, or OneDrive). This is because most of these special folders make the contents available on demand and offload the content to the cloud (rather than having the files available locally).
    ```

1. **What is the Code Editor you want to use?** All of the instructions and demos will be using Visual Studio Code (and that's what we recommend), but you're welcome to use other interactive development environments (IDEs) if you like.


1. **Which Terminal do you intend to use?**
    - On macOS and Ubuntu, we suggest using the built-in Terminal and/or the Terminal that is embedded into Visual Studio Code.


## Instructions

Now that you've answered all the prep questions, it's time to set up your working environment!

```{tip}
In the instructions below, replace `OPB` with the course like `CPSC210` and replace `instructor_subject_bank` with the course repository: `pl-ubc-cpsc210`.
```

1. Create a parent directory for this project called `OPB` wherever you decided to work locally on your machine.

1. Clone the `instructor_subject_bank` locally in the `OPB` directory, and then`cd`

    ```
    git clone git@github.com:open-resources/instructor_physics_bank.git
    ```

1. Change directory to the parent directory:

    ```
    /Users/pixiedust/Desktop/OPB/instructor_subject_bank
    ```

1. Run the command to install the pre-commit hooks locally in the `instructor_subject_bank` directory:

    ```
    pre-commit install
    ```

Now you're ready to continue configuring and installing Docker!

```{tip}
Often we will want to hide certain files from the VS Code.
For example, the `.ipynb_checkpoints` directory.
To do this, follow the directions [here](https://www.w3schools.io/editor/vscode-hide-files-folder/).
```
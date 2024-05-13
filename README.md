
# CTF Challenges Repository

[中文](README_zh.md) | [English](README.md)

## Introduction

Welcome to our Docker for AutoCTF repository! This project is dedicated to exploring the feasibility of solving CTF challenge topics using large-scale language models.

In this repository, we aim to collect a wide variety of Web challenge topics in CTF as data support for researching automated solutions to Web topics in CTF. We believe that through our collective efforts, we can uncover new strategies, techniques, and perhaps even automate aspects of CTF topics that have never been automated before.

## Repository Structure

The repository is organized as follows:

```
.
|-- docker-compose.yml
|-- readme.md
`-- challenge_folder
    |-- challenge_files
```

- **docker-compose.yml**: Docker file that sets up the challenge environment and contains the ports that need to be open.
- **Readme.md**: Contains a description of the challenge, its difficulty level, any necessary hints, and an explanation of the challenge.
- **challenge_folder/**: Directory of challenge files (e.g., web1).

Note that the structure does not have to follow this format exactly, but should contain files such as docker-compose.yml, the challenge folder, and a description of the challenge problem.

## Contribution Guide


Contributions are highly encouraged! Whether it's adding a new challenge, improving an existing challenge, or suggesting a new feature.

To contribute, follow these steps:

1. Fork the repository.
2. Add your title according to the repository structure above.
3. Make sure your `Readme.md `contains the challenge description, difficulty rating, any necessary hints, and an explanation of the challenge.
4. Create a pull request that briefly describes your challenge and its difficulty.

## Notices and Acknowledgements

This project uses the following open source projects and resources：

- [CTFTraining](https://github.com/CTFTraining/CTFTraining)
- [ctf_challenges](https://github.com/le31ei/ctf_challenges)
- [sus_WPs](https://github.com/susers/Writeups/tree/master)

We thank the authors and contributors of these projects for their contributions to the open source community.

## Purpose and Disclaimer

This project (project name) is created and maintained for scientific research and educational purposes only. It incorporates a number of other open-source projects, tools, and resources, aimed at exploring and studying techniques and methods in the field of information security. This project does not encourage any form of illegal activities or misuse, and the owner(s) and contributors of this project will not be responsible for any direct or indirect consequences that arise from the use of this project's content.

When using this project and its content, please ensure that your actions comply with local laws and ethical standards, and that you fully understand the risks involved.

If the content violates your rights and interests,please contact tedlau@gmail.com, we will remove the content at the first time.

## License

This repository follows the MIT license. Please refer to the [LICENSE](LICENSE) file for more information.

# Identifying Patterns of Inaccurate Time Estimations for Issue Resolution in Software Development

## Getting Started

This project's working branch is `main`, and it has the following directory structure:

```
[REPOSITORY-Name]
	├── LICENSE.md
	├── requiremnets.txt
	├── README.md
	├── data
	│   ├── raw
	│   └── processed
	├── docs
	│   └── support documentation and project descriptions
	└── src
	    └── all executbale script files
```

## Running the App

1. Clone the project
	```bash
	git clone https://github.com/abroniewski/Jira-Dataset-Time-Estimate-Study.git
	```
2. Install dependencies listed in requirements.txt
3. Download [The Public Jira Dataset](https://zenodo.org/record/5901804/files/2022.01.25%20-%20ThePublicJiraDataset.zip?download=1) into a `../data` directory at the project parent level.

[//]: # (4. run `main.py`)

[//]: # (	```bash)

[//]: # (	python main.py)

[//]: # (	```)

[//]: # ()
[//]: # (This will use the data located in `data/raw` and run through the full data pipeline.)

## Development

> The goal of this project is to:
> 1. Determine the accuracy of time estimation for different project types
> 2. Identify if there are characteristics of issues that result in more or less accurate time estimations

The work is completed in stages:

1. Explore to see what different types of issues exist and if all of them are relevant to the study 
2. Explore statistics for each project (number of issues, average number of sub-tasks per issue, issues types, length of time of project, overlap between creators and assignee's)
3. Create subsets of project data
4. Determining the typical accuracy of time estimates to resolve issues
5. Identify if there are specific characteristics of issues that are correlated with inaccurate time estimates or accurate time estimates using an analysis of variance (ANOVA)

## Authors

#### Adam Broniewski

* [GitHub](https://github.com/abroniewski)
* [LinkedIn](https://www.linkedin.com/in/abroniewski/)
* [Website](https://adambron.com)

#### Himanshu Choudhary

* [GitHub](https://github.com/himanshudce)
* [LinkedIn](https://www.linkedin.com/in/himanshudce/)

#### Tejaswini Dhupad

* [GitHub](https://github.com/tejaswinidhupad)
* [LinkedIn](https://www.linkedin.com/in/tejaswinidhupad/)

#### Luiz Fonseca

* [GitHub](https://github.com/fonluiz)
* [LinkedIn](https://www.linkedin.com/in/luiz-alberto-fonseca/)

## License

This project is open source software [licensed as MIT][license].

## Acknowledgments


[license]: https://github.com/abroniewski/LICENSE.md

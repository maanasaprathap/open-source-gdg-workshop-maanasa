<h1>React Project for Beginners Repository</h1>

Welcome to the React Project for Beginners Repository! This is a special place for beginners passionate about learning and contributing to React JS open-source projects.
(85 ++ Projects)
<h3>NOTE#1: PLEASE CHECK YOUR PROJECT CAREFULLY, IT SHOULD BE ERROR-FREE, YOUR PROJECT WILL BE REVIEWED, IF THE REVIEWER FOUND ANY ERROR YOUR REQUEST WILL MARKED AS "INVALID".<h3>

<h3>NOTE#2: DON'T FORGET TO LIST YOUR PROJECT IN THE `projects.js` FILE IN THE ROOT FOLDER OF THE REPO. YOU CAN ALSO ADD THE DEMO LINK OF YOUR PROJECT(IF ANY)<h3>
<h3>NOTE #3: Please read the <a href="https://github.com/ianshulx/React-projects-for-beginners/blob/main/Repo_Size_Guidelines">Repo-Size Management Guidelines</a>.</h3>

  
<h3>Description</h3>

This repository serves as a platform for React Project for Beginners participants who are on their journey to mastering React JS and want to contribute per Hacktoberfest. It's a place where you can share your mini-projects, learn from others, and contribute to the growth of the open-source community.

Whether you've built a simple calculator, a to-do list, or a weather app, your contributions are welcomed here. The main goal of this repository is to encourage learning and collaboration among developers who are new to React and open-source contributions.

<h3>What is Hacktoberfest?</h3>

Hacktoberfest is a month-long celebration of open-source software run by DigitalOcean. It's open to everyone in our global community. Whether you’re a developer, a student learning to code, an event host, or a company of any size, you can help drive the growth of open-source and make positive contributions to an ever-growing community. All backgrounds and skill levels are encouraged to complete the challenge.
[Click Here for Hacktoberfest Information](https://hacktoberfest.com/)



### Installation Steps

1) Clone the repo using git clone git@github.com:maanasaprathap/open-source-gdg-workshop-maanasa.git
or
git clone https://github.com/maanasaprathap/open-source-gdg-workshop-maanasa.git

2) cd (select directory)
3) npm install
4) npm start / npm run dev
   

### Process of Contribution

1._Fork_ : Fork this GitHub Repo to your own github account
2._Clone_ : Clone the forked repo (the repo present on your account) to your local machine (reminder : make sure you are in the directory where you want the repository stored).

```terminal
git clone git@github.com:maanasaprathap/open-source-gdg-workshop-maanasa.git
or
git clone https://github.com/maanasaprathap/open-source-gdg-workshop-maanasa.git
```

3.Create a _new Branch_

```markdown
git checkout -b my-new-branch
```

4._Changes_ : Create a new branch and commit your changes on that branch.
5._ADD_ and _COMMIT_

- Add your changes

```markdown
git add .
```

- Commit your changes. (reminder : make sure your relevant message includes the necessary detail to understand the change(s))

```markdown
git commit -m "Relevant message"
```

6._Push_ : After all changes are commited, push your changes to your remote repo.

```markdown
git push origin my-new-branch
```

7._PR_ : After pushing changes, raise a PR from your remote repo to this repo's dev branch (reminder : make sure you title your PR appropriately to understand the major topic of your request)

   
By participating in this repository, you will not only be contributing to the open source, but also improving your skills in React JS. Let's make learning React fun and interactive during this Hacktoberfest!
Happy Coding and Happy Hacktoberfest!

<h3>Contribution Guidelines</h3>
Please make sure to follow the contribution guidelines before making a pull request. Quality contributions are what make the open-source community an amazing place to learn, inspire, and create.

Find the full list of guidelines in the CONTRIBUTING.md file.

<h3> Repo-Size Management Guidelines</h3>

This repository hosts multiple projects, and to ensure smooth performance and efficient management, the following guidelines must be followed:

## 1. Project Size Limitation
- Each individual project folder should **not exceed 15 MB**.
- If a project requires more space due to additional assets or data, consider refactoring the code or storing external files in a separate location (such as cloud storage or GitHub Pages).

## 2. File Organization
- Projects should be organized in clearly labeled folders under the root directory.
- Keep the folder structure simple, e.g., `Project_name1/`, `Project_name2/`, etc.

## 3. Avoid Large Binary Files
- Do **not** commit large binary files (e.g., videos, high-resolution images, compiled executables) directly to the repository.
- Use [Git LFS (Large File Storage)](https://git-lfs.github.com/) for files larger than **100 MB** or consider storing large assets outside the repository and linking to them.

## 4. Minimize External Libraries
- Minimize the use of heavy third-party libraries or external dependencies.
- Use a `.gitignore` file to exclude unnecessary or autogenerated files (e.g., `node_modules/`, `build/`, etc.).

## 5. Regular Cleanup
- Perform regular cleanup of unnecessary files (e.g., logs, temporary files).
- Remove outdated or unused code, assets, or projects from the repository.

## 6. Compression of Assets
- **Image Compression**: Use tools like [TinyPNG](https://tinypng.com/), [ImageOptim](https://imageoptim.com/), or [Squoosh](https://squoosh.app/) to compress images (PNG, JPEG, etc.) before committing them.
  - **For Web Images**: Use appropriate formats like **WebP** to significantly reduce size without compromising quality.
- **Limit Resolution**: Avoid using high-resolution images unnecessarily. For most React projects, a resolution of 72 DPI (dots per inch) is sufficient for the web.
- **SVG Usage**: Use **SVG** files whenever possible for vector graphics, as they are scalable and lightweight.
- Compress other assets like PDFs and audio files using lossless compression tools before adding them to the repository to reduce file size.

## 7. Optimize Code for Performance
- **Bundle and Minify**: Ensure your project setup uses tools like Webpack or Vite to bundle and minify JavaScript and CSS files. This reduces file sizes and speeds up load times.
- **Tree Shaking**: When using third-party libraries, make sure to only import the necessary parts (tree-shaking) to avoid bundling unused code.
  - For example, prefer `import { Button } from 'library'` instead of `import * as Library from 'library'`.

## 8. Versioning and History Management
- Keep commit history clean by avoiding frequent commits of unnecessary files.
- Use meaningful and concise commit messages.
- If a project becomes too large over time, consider splitting it into a separate repository.

## 9. Contributions
- For contributors, please adhere to the project size limits. Large contributions should be discussed through an issue or a pull request.
- Ensure all contributions are optimized for size and performance before submitting them.



<h3>Code of Conduct</h3>

This project adheres to the Hacktoberfest Values ↗ and the Contributor Covenant Code of Conduct ↗. By participating, you are expected to uphold this code.
In addtiona this project 


<h3>License</h3>

This repository is licensed under the MIT License.

The MIT License Do's and Dont's summary:

Do's: 
Use the code in commercial applications: For example, a company can create a proprietary piece of software that includes all or part of the original open source code, then charge money for that software.
Modify the code: In other words, developers can change/update the code however they’d like.
Distribute copies of the code and any modifications: As long as the original copyright notice and the license itself are included, an organization can distribute and sell copies or modified versions of the code.
Sublicense the code: This means you can incorporate the original code into a modification with a stricter license.

Dont's:
Can’t hold the code author(s) legally liable for any reason.
Can’t delete the copyright notice and original license from your version of the code.

Let's start contributing and make the open-source community a better place for everyone!
<h1>React Project for Beginners Repository</h1>

Welcome to the React Project for Beginners Repository! This is a special place for beginners who are passionate about learning and contributing to open-source projects using React JS.
Its Hacktoberfest currently!
<h3>NOTE#1: PLEASE CHECK YOUR PROJECT CAREFULLY, IT SHOULD BE ERROR-FREE, YOUR PROJECT WILL BE REVIEWED, IF THE REVIEWER FOUND ANY ERROR YOUR REQUEST WILL MARKED AS "INVALID".<h3>

<h3>NOTE#2: DON'T FORGET TO LIST YOUR PROJECT IN THE `projects.js` FILE IN THE ROOT FOLDER OF THE REPO. YOU CAN ALSO ADD THE DEMO LINK OF YOUR PROJECT(IF ANY)<h3>
<h3> NOTE#3: Please read [Repo-Size Management Guidelines](https://github.com/ianshulx/React-projects-for-beginners/blob/main/Repo_Size_Guidelines) </h3>
  
<h3>Description</h3>

This repository serves as a platform for React Project for Beginners participants who are on their journey to mastering React JS and want to contribute per Hacktoberfest. It's a place where you can share your mini-projects, learn from others, and contribute to the growth of the open-source community.

Whether you've built a simple calculator, a to-do list, or a weather app, your contributions are welcomed here. The main goal of this repository is to encourage learning and collaboration among developers who are new to React and open-source contributions.

<h3>What is Hacktoberfest?</h3>

Hacktoberfest is a month-long celebration of open-source software run by DigitalOcean. It's open to everyone in our global community. Whether you’re a developer, a student learning to code, an event host, or a company of any size, you can help drive the growth of open-source and make positive contributions to an ever-growing community. All backgrounds and skill levels are encouraged to complete the challenge.
[Click Here for Hacktoberfest Information](https://hacktoberfest.com/)

### Process of Contribution

1._Fork_ : Fork this GitHub Repo to your own github account
2._Clone_ : Clone the forked repo (the repo present on your account) to your local machine (reminder : make sure you are in the directory where you want the repository stored).

```terminal
git clone git@github.com:maanasaprathap/open-source-gdg-workshop-maanasa.git
or
git clone https://github.com/maanasaprathap/open-source-gdg-workshop-maanasa.git
```

3.Create a _new Branch_

```markdown
git checkout -b my-new-branch
```

4._Changes_ : Create a new branch and commit your changes on that branch.
5._ADD_ and _COMMIT_

- Add your changes

```markdown
git add .
```

- Commit your changes. (reminder : make sure your relevant message includes the necessary detail to understand the change(s))

```markdown
git commit -m "Relevant message"
```

6._Push_ : After all changes are commited, push your changes to your remote repo.

```markdown
git push origin my-new-branch
```

7._PR_ : After pushing changes, raise a PR from your remote repo to this repo's dev branch (reminder : make sure you title your PR appropriately to understand the major topic of your request)

   
By participating in this repository, you will not only be contributing to the open source, but also improving your skills in React JS. Let's make learning React fun and interactive during this Hacktoberfest!
Happy Coding and Happy Hacktoberfest!

<h3>Contribution Guidelines</h3>
Please make sure to follow the contribution guidelines before making a pull request. Quality contributions are what make the open-source community an amazing place to learn, inspire, and create.

Find the full list of guidelines in the CONTRIBUTING.md file.

<h3> Repo-Size Management Guidelines</h3>

This repository hosts multiple projects, and to ensure smooth performance and efficient management, the following guidelines must be followed:

## 1. Project Size Limitation
- Each individual project folder should **not exceed 15 MB**.
- If a project requires more space due to additional assets or data, consider refactoring the code or storing external files in a separate location (such as cloud storage or GitHub Pages).

## 2. File Organization
- Projects should be organized in clearly labeled folders under the root directory.
- Keep the folder structure simple, e.g., `Project_name1/`, `Project_name2/`, etc.

## 3. Avoid Large Binary Files
- Do **not** commit large binary files (e.g., videos, high-resolution images, compiled executables) directly to the repository.
- Use [Git LFS (Large File Storage)](https://git-lfs.github.com/) for files larger than **100 MB** or consider storing large assets outside the repository and linking to them.

## 4. Minimize External Libraries
- Minimize the use of heavy third-party libraries or external dependencies.
- Use a `.gitignore` file to exclude unnecessary or autogenerated files (e.g., `node_modules/`, `build/`, etc.).

## 5. Regular Cleanup
- Perform regular cleanup of unnecessary files (e.g., logs, temporary files).
- Remove outdated or unused code, assets, or projects from the repository.

## 6. Compression of Assets
- **Image Compression**: Use tools like [TinyPNG](https://tinypng.com/), [ImageOptim](https://imageoptim.com/), or [Squoosh](https://squoosh.app/) to compress images (PNG, JPEG, etc.) before committing them.
  - **For Web Images**: Use appropriate formats like **WebP** to significantly reduce size without compromising quality.
- **Limit Resolution**: Avoid using high-resolution images unnecessarily. For most React projects, a resolution of 72 DPI (dots per inch) is sufficient for the web.
- **SVG Usage**: Use **SVG** files whenever possible for vector graphics, as they are scalable and lightweight.
- Compress other assets like PDFs and audio files using lossless compression tools before adding them to the repository to reduce file size.

## 7. Optimize Code for Performance
- **Bundle and Minify**: Ensure your project setup uses tools like Webpack or Vite to bundle and minify JavaScript and CSS files. This reduces file sizes and speeds up load times.
- **Tree Shaking**: When using third-party libraries, make sure to only import the necessary parts (tree-shaking) to avoid bundling unused code.
  - For example, prefer `import { Button } from 'library'` instead of `import * as Library from 'library'`.

## 8. Versioning and History Management
- Keep commit history clean by avoiding frequent commits of unnecessary files.
- Use meaningful and concise commit messages.
- If a project becomes too large over time, consider splitting it into a separate repository.

## 9. Contributions
- For contributors, please adhere to the project size limits. Large contributions should be discussed through an issue or a pull request.
- Ensure all contributions are optimized for size and performance before submitting them.



<h3>Code of Conduct</h3>

This project adheres to the Hacktoberfest Values ↗ and the Contributor Covenant Code of Conduct ↗. By participating, you are expected to uphold this code.
In addtiona this project 


<h3>License</h3>

This repository is licensed under the MIT License.

The MIT License Do's and Dont's summary:

Do's: 
Use the code in commercial applications: For example, a company can create a proprietary piece of software that includes all or part of the original open source code, then charge money for that software.
Modify the code: In other words, developers can change/update the code however they’d like.
Distribute copies of the code and any modifications: As long as the original copyright notice and the license itself are included, an organization can distribute and sell copies or modified versions of the code.
Sublicense the code: This means you can incorporate the original code into a modification with a stricter license.

Dont's:
Can’t hold the code author(s) legally liable for any reason.
Can’t delete the copyright notice and original license from your version of the code.

Let's start contributing and make the open-source community a better place for everyone!
<h1>React Project for Beginners Repository</h1>

Welcome to the React Project for Beginners Repository! This is a special place for beginners who are passionate about learning and contributing to open-source projects using React JS.
Its Hacktoberfest currently!
<h3>NOTE#1: PLEASE CHECK YOUR PROJECT CAREFULLY, IT SHOULD BE ERROR-FREE, YOUR PROJECT WILL BE REVIEWED, IF THE REVIEWER FOUND ANY ERROR YOUR REQUEST WILL MARKED AS "INVALID".<h3>

<h3>NOTE#2: DON'T FORGET TO LIST YOUR PROJECT IN THE `projects.js` FILE IN THE ROOT FOLDER OF THE REPO. YOU CAN ALSO ADD THE DEMO LINK OF YOUR PROJECT(IF ANY)<h3>
<h3> NOTE#3: Please read [Repo-Size Management Guidelines](https://github.com/ianshulx/React-projects-for-beginners/blob/main/Repo_Size_Guidelines) </h3>
  
<h3>Description</h3>

This repository serves as a platform for React Project for Beginners participants who are on their journey to mastering React JS and want to contribute per Hacktoberfest. It's a place where you can share your mini-projects, learn from others, and contribute to the growth of the open-source community.

Whether you've built a simple calculator, a to-do list, or a weather app, your contributions are welcomed here. The main goal of this repository is to encourage learning and collaboration among developers who are new to React and open-source contributions.

<h3>What is Hacktoberfest?</h3>

Hacktoberfest is a month-long celebration of open-source software run by DigitalOcean. It's open to everyone in our global community. Whether you’re a developer, a student learning to code, an event host, or a company of any size, you can help drive the growth of open-source and make positive contributions to an ever-growing community. All backgrounds and skill levels are encouraged to complete the challenge.
[Click Here for Hacktoberfest Information](https://hacktoberfest.com/)

### Process of Contribution

1._Fork_ : Fork this GitHub Repo to your own github account
2._Clone_ : Clone the forked repo (the repo present on your account) to your local machine (reminder : make sure you are in the directory where you want the repository stored).

```terminal

git clone https://github.com/maanasaprathap/open-source-gdg-workshop-maanasa.git
or 
git clone https://github.com/maanasaprathap/open-source-gdg-workshop-maanasa.git
```

3.Create a _new Branch_

```markdown
git checkout -b my-new-branch
```

4._Changes_ : Create a new branch and commit your changes on that branch.
5._ADD_ and _COMMIT_

- Add your changes

```markdown
git add .
```

- Commit your changes. (reminder : make sure your relevant message includes the necessary detail to understand the change(s))

```markdown
git commit -m "Relevant message"
```

6._Push_ : After all changes are commited, push your changes to your remote repo.

```markdown
git push origin my-new-branch
```

7._PR_ : After pushing changes, raise a PR from your remote repo to this repo's dev branch (reminder : make sure you title your PR appropriately to understand the major topic of your request)

   
By participating in this repository, you will not only be contributing to the open source, but also improving your skills in React JS. Let's make learning React fun and interactive during this Hacktoberfest!
Happy Coding and Happy Hacktoberfest!

<h3>Contribution Guidelines</h3>
Please make sure to follow the contribution guidelines before making a pull request. Quality contributions are what make the open-source community an amazing place to learn, inspire, and create.

Find the full list of guidelines in the CONTRIBUTING.md file.

<h3> Repo-Size Management Guidelines</h3>

This repository hosts multiple projects, and to ensure smooth performance and efficient management, the following guidelines must be followed:

## 1. Project Size Limitation
- Each individual project folder should **not exceed 15 MB**.
- If a project requires more space due to additional assets or data, consider refactoring the code or storing external files in a separate location (such as cloud storage or GitHub Pages).

## 2. File Organization
- Projects should be organized in clearly labeled folders under the root directory.
- Keep the folder structure simple, e.g., `Project_name1/`, `Project_name2/`, etc.

## 3. Avoid Large Binary Files
- Do **not** commit large binary files (e.g., videos, high-resolution images, compiled executables) directly to the repository.
- Use [Git LFS (Large File Storage)](https://git-lfs.github.com/) for files larger than **100 MB** or consider storing large assets outside the repository and linking to them.

## 4. Minimize External Libraries
- Minimize the use of heavy third-party libraries or external dependencies.
- Use a `.gitignore` file to exclude unnecessary or autogenerated files (e.g., `node_modules/`, `build/`, etc.).

## 5. Regular Cleanup
- Perform regular cleanup of unnecessary files (e.g., logs, temporary files).
- Remove outdated or unused code, assets, or projects from the repository.

## 6. Compression of Assets
- **Image Compression**: Use tools like [TinyPNG](https://tinypng.com/), [ImageOptim](https://imageoptim.com/), or [Squoosh](https://squoosh.app/) to compress images (PNG, JPEG, etc.) before committing them.
  - **For Web Images**: Use appropriate formats like **WebP** to significantly reduce size without compromising quality.
- **Limit Resolution**: Avoid using high-resolution images unnecessarily. For most React projects, a resolution of 72 DPI (dots per inch) is sufficient for the web.
- **SVG Usage**: Use **SVG** files whenever possible for vector graphics, as they are scalable and lightweight.
- Compress other assets like PDFs and audio files using lossless compression tools before adding them to the repository to reduce file size.

## 7. Optimize Code for Performance
- **Bundle and Minify**: Ensure your project setup uses tools like Webpack or Vite to bundle and minify JavaScript and CSS files. This reduces file sizes and speeds up load times.
- **Tree Shaking**: When using third-party libraries, make sure to only import the necessary parts (tree-shaking) to avoid bundling unused code.
  - For example, prefer `import { Button } from 'library'` instead of `import * as Library from 'library'`.

## 8. Versioning and History Management
- Keep commit history clean by avoiding frequent commits of unnecessary files.
- Use meaningful and concise commit messages.
- If a project becomes too large over time, consider splitting it into a separate repository.

## 9. Contributions
- For contributors, please adhere to the project size limits. Large contributions should be discussed through an issue or a pull request.
- Ensure all contributions are optimized for size and performance before submitting them.



<h3>Code of Conduct</h3>

This project adheres to the Hacktoberfest Values ↗ and the Contributor Covenant Code of Conduct ↗. By participating, you are expected to uphold this code.
In addtiona this project 


<h3>License</h3>

This repository is licensed under the MIT License.

The MIT License Do's and Dont's summary:

Do's: 
Use the code in commercial applications: For example, a company can create a proprietary piece of software that includes all or part of the original open source code, then charge money for that software.
Modify the code: In other words, developers can change/update the code however they’d like.
Distribute copies of the code and any modifications: As long as the original copyright notice and the license itself are included, an organization can distribute and sell copies or modified versions of the code.
Sublicense the code: This means you can incorporate the original code into a modification with a stricter license.

Dont's:
Can’t hold the code author(s) legally liable for any reason.
Can’t delete the copyright notice and original license from your version of the code.

Let's start contributing and make the open-source community a better place for everyone!

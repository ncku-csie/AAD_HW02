# AAD_HW02

This repository include **starter code**, **Espresso AndroidTest** and **Travis setting**, which are used for automatically grading in **Android Application Development course in National Cheng Kung University (NCKU)** in 2019 Spring Semester.

Materials:
- **Lesson 2: Activities and intents** in Codelabs for Android Developer Fundamentals (V2). 
<https://developer.android.com/courses/fundamentals-training/toc-v2>

Feel free to fork this repository if you are also working on this codelab and want to testing your answer.
For more instructions, please follow the [homework rules slides](https://github.com/ncku-csie/AAD_HW01/blob/master/Homework%20Rules.pdf). 
If you have further questions, please contact android@imslab.org

These test cases are written by Intelligent Mobile Service laboratory and Cyber Physical System Laboratory in NCKU.

---
Please follow the instructions on the **Homework** sections in these codelabs.

- [02.1: Activities and intents](https://codelabs.developers.google.com/codelabs/android-training-create-an-activity/index.html?index=..%2F..%2Fandroid-training#11)
- [02.2: Activity lifecycle and state](https://codelabs.developers.google.com/codelabs/android-training-activity-lifecycle-and-state/index.html?index=..%2F..%2Fandroid-training#8)
- [02.3: Implicit intents](https://codelabs.developers.google.com/codelabs/android-training-activity-with-implicit-intent/index.html?index=..%2F..%2Fandroid-training#11)


## Part 1. Questions (20 pt)
Please submit your answer on moodle.
<https://moodle.ncku.edu.tw/course/view.php?id=104771>

**[Notice]** 
- You only have **one chance** to submit your answer.
- Your score on moodle (out of 100) * 20 % = your points in this part. <br>
For example, you score on moodle is 50, and then you got 50 * 20 % = 10 pt for this homework

| Codelab | Questions |
| --- | ----------- |
| 02.1 | 5 Questions |
| 02.2 | 4 Questions |
| 02.3 | 3 Questions |


## Part 2. Android Tests (80 pt)

Please submit your code to the **master** branch in this repository for grading.

**[Notice]** 
- Please do not modify the following files:
    - .travis.yml
    - <Project>/app/src/androidTest/*
    - gradle files
- Once any modifications or any cheating behavior are detected, you will got 0 pt for this homework.
- Creating a new branch to develop and testing locally are highly recommended.
    
<table>
    <thead>
        <tr>
            <th>Codelab</th>
            <th>Starter Code</th>
            <th>Questions</th>
            <th>Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2>02.1</td>
            <td rowspan=2>HelloToast</td>
            <td>newActivityLaunchTest</td>
            <td>20 pt</td>
        </tr>
        <tr>
            <td>buttonTextTest</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td rowspan=2>02.2</td>
            <td rowspan=2>CounterHomework</td>
            <td>viewTest</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>saveValueTest</td>
            <td>15 pt</td>
        </tr>
        <tr>
            <td rowspan=2>02.3</td>
            <td rowspan=2>ImplicitIntents</td>
            <td>testTakePictureButtonLocation</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>takePictureActionTest</td>
            <td>15 pt</td>
        </tr>
    </tbody>
</table>

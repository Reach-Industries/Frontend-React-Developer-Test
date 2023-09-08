<p align="center">
<img src=https://github.com/Reach-Industries/Senior-Frontend-React-Developer-Test/blob/8143d4f719e9e690bb8a669dea8249ce367470c4/RI-Sen-FE-React.png/>
</p>

# Test Introduction

At Reach Industries, we are building innovative products that leverage high-volume data streaming and cloud based AI. Our LabEye camera systems are specifically designed for lab environments where precision and detail are paramount. Our customers seamlessly integrate LabEyes into their setups to capture high-quality visual data. This raw data is then securely transmitted to Lumi, our advanced cloud-based platform. 

Lumi harnesses the power of state-of-the-art algorithms to process this data, converting the visual inputs into actionable quantitative values. One of the standout features of our system is its ability to overlay the derived data directly onto the original video in real-time. This not only allows researchers and lab technicians to see the data but also to interactively visualize the insights and patterns that Lumi has discerned, enhancing their understanding and decision-making processes.

This assessment will centre around building a single page application, fetching remote data and displaying synchronised video and annotation information.
You should design your work as if it were something you will be iterating on in the future in collaboration with other people - you won’t actually be doing this, but this should be considered in your decisions and code style.

# Task

You have been provided with two remote data sources for a 20-second observation:

- An mp4 video [here](https://reach-industries-candidate-tests.s3.eu-west-2.amazonaws.com/FrontendCandidateTest-FINAL.mp4).
- Annotation data in JSON format [here](https://reach-industries-candidate-tests.s3.eu-west-2.amazonaws.com/FrontendCandidateTest-FINAL.json).

The main goal is to display the video with the provided data visualized on top of it.
Required Features:
- A header containing the title “Reach Industries Frontend Assessment”.
- A sidebar listing available videos (please add mock entries for demonstration purposes).
- A main pane that includes:
  - The playable, scrubbable video with annotations.
  - Raw data of the currently displayed video frame.
  - The complete raw JSON in a toggleable section.
  - A button to download the entire JSON.

## Notes

- Fetch data from the provided URLs during runtime.
- Some video frames might lack data.
- The design should display on a single page without scrolling or inaccessible clipped overflow.

## Bonus Task

- Make the application responsive for mobile with the sidebar becoming a slide-in hamburger menu.

# Setup & Environment

Must use
- TypeScript.
- React.

# Deliverables & How to submit

- Code uploaded to GitHub (either as a public repo or private repo).
- The repo should be easily runnable or buildable without additional intervention from the evaluators.
- A usable demo deployment of the app (Vercel, GitHub Pages etc).
- Detailed notes in the repository's README.md. Explain the libraries you've used, any resources you've referenced, your design approach, and any constraints you faced. Your insights and the clarity of your explanation in this section are critical.

## Delivery Bonus

- Dockerised Repo with an automated build process.

# Evaluation Criteria

You will be marked on:
- Your code quality.
- Your project organisation.
- The clarity, aesthetics and usability of your application (only a basic effort is required).
- The efficiency of your approach to providing a solution.
- The rationale you provide for the approach you have taken (in comments or in supporting documents).

# FAQ
## 1. Do I need to set up any specific environment or version of TypeScript and React for this assessment?
- No, as long as they are valid builds of TypeScript and React

## 2. Is there a preferred method or tool for fetching the remote data?
- No. 

## 3. Can I use libraries or packages to complete technical parts of the test?
- Absolutely. Please approach this test in the same way you would approach a standard piece of work. As stated previously, the only stipulation is you must use React and Typescript.

# Troubleshooting & Support
Who @Reach.Industries?

# Terms & Conditions for Interview Tests

## 1. Purpose of the Test
This test is designed to evaluate the technical prowess, problem-solving skills, and overall knowledge of the applicant. The test tasks and questions reflect challenges and scenarios the company has already addressed internally. Our goal is to gauge your approach and compare it with solutions we have already devised.

## 2. Use of Test Results
- We emphasize that the tasks presented in the tests have already been achieved by our internal team to a high standard.
- The solutions provided by candidates will purely be for evaluation purposes and will not be used in any of our products or services.
- Any resemblance between our products and a test submission is purely coincidental. We have no intention or motive to replicate your solution in our offerings.
- We will not store or retain your test results post-evaluation.

## 3. Feedback and Next Steps
Feedback may or may not be provided post-test based on company discretion. Candidates are encouraged to engage in the review meeting for a detailed understanding of their performance.

## 4. Modifications & Updates
Reach Industries reserves the right to modify these terms and conditions without prior notice. It's advised to review these T&Cs before proceeding with the test.

## 5. Consent
By participating in this test, candidates agree to these terms and conditions.

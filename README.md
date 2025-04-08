# ethology: OCTRON (Laurel Humphrey)

## Personal details
- **Full name:** Laurel Humphrey
- **Email:** laurelhumphrey24@gmail.com
- **GitHub username:** laurelhumphrey
- **Zulip username:** Laurel Humphrey
- **Location & time-zone:** USA (UTC-05:00)
- **Personal website / project portfolio:** [Project OCTRON](https://github.com/horsto/OCTRON)
- **Code contribution:** 
- **Proposal discussion link:**

## Project proposal 

**Synopsis**

We envision OCTRON as an extension of the ethology project within the NIU GSoC initiative. We propose it as an alternative to existing markerless tracking algorithms, particularly key point tracking algorithms (DLC, SLEAP, etc.). OCTRON facilitates markerless segmentation for custom training dataset generation and subsequent training of custom models, enabling segmentation and tracking of objects across video frames. In the future, we aim for OCTRON's output to be compatible with the movement package, allowing anchor point tracking methods to be used alongside segmentation data generated by OCTRON. OCTRON is in the early stages of development. While we have a working version, several improvements are needed to make it a maintainable and usable open-source community contribution. These improvements include code maintainability, documentation, and further development of core OCTRON functions.

<img width="1247" alt="Screenshot 2025-04-07 at 8 52 19 PM" src="https://github.com/user-attachments/assets/43f40a7b-5278-4adf-963e-700ac73ff146" />


**Implementation timeline**

**Minimal Deliverables:**

*   Code maintainability
      *   Structure of the repository and organization of the codebase.
      *   Code testing (code coverage, etc.).
      *   Contribution guidelines and onboarding for new contributors.

*   Documentation
      *   Complete code documentation website, for example hosted on GitHub via MkDocs.
      *   Usability improvements and further development
      *   Utilities for curating OCTRON output, such as stitching/merging tracks that have been artificially separated (high priority).
      *   Analysis video generation and other useful features for processing OCTRON outputs (medium priority).

*   Stretch goals (if time allows)
      *   Integration of key point tracking into YOLO training (medium priority).
      *   Integration of OCTRON with existing tools in the NIU codebase, like movement (see introduction above) (high priority).


**Weekly Timeline:**
*   **Total Duration:** 10 weeks (~90h small project size)
*   **Estimated Weekly Hours:** 8-10 hours/week

| Week | Task                                                                                |
|------|-------------------------------------------------------------------------------------|
| 0    | Community bonding. Introduce OCTRON to mentors and discuss potential improvements.  |
| 1    | Create code documentation website. Begin bug tracking and code testing.             |
| 2    | Curate OCTRON output.                                                               |
| 3    | Integrate key point tracking into YOLO training.                                    |
| 4    | Integrate OCTRON with tools in NIU codebase.                                        |
| 5    | Add features for processing OCTRON outputs.                                         |
| 6    | Organize the codebase and repository structure.                                     |
| 7    | Create guidelines for new contributors.                                             |
| 8    | Update user documentation to reflect improvements.                                  |
| 9    | Finalize code testing, repository, and documentation website.                       |
| 10   | Review and resolve final issues. Prepare final materials for submission.            |


**Communication plan**

I am flexible to communicate with my mentor regularly as needed. Weekly video call meetings would be helpful to give progress updates as I move through my deliverables and to ask questions on areas where I need more guidance. I will also be available via Zulip chat to ask for troubleshooting help and work through errors as needed throughout the week.

## Personal statement

**Past experience:** 
    
So far, I have been working with the OCTRON developer Horst Obenhaus to test its usage on various animal behavior videos and evaluate the results. This involves annotating videos of various animal species behaviors to create a machine learning tracker through the OCTRON gui, working through errors, and evaluating the effectiveness of the model. I hope to contribute further improvements to this tool with the help of GSoC and NIU mentorship.

My past programming experience includes using Linux, high-performance computing, Python, and R to conduct bioinformatics research assembling and annotating the genomes of endangered species for comparative analysis. I am involved in ongoing publications to document the novel genome assemblies of corals and other organisms, and have contributed to the testing of an open source genome assembly pipeline Argonaut on GitHub.
   
**Motivation: why this project?**

I am interested in this project because I believe OCTRON will be a valuable alternative to existing key point tracking algorithms and a resource for various scientists to further study animal behavior tracking. I was drawn to Horst's research goals of tracking octopus sleep patterns through video data and how this napari plugin could improve the efficiency and effectiveness of his research as well as the research of others in the open source community. This opportunity relates to my own goals of exploratory research on marine animal behaviors as well as developing my bioinformatics skills through open source code development and refinement.

**Match: why you?**

My experience with testing OCTRON so far on various datasets as well as my previous computational biology background and passion for this project make me a great fit for this opportunity. Through working on this project and others I have gained skills in troubleshooting errors, building code, improving user experience, and science accessibility which I hope to build upon by bringing this new tool to the GSoC community.
  
**Availability:**

During this time I will be working a regular job 40 hours per week, so I plan to allocate around 2 hours after each work day to my GSoC work.

## GSoC

**GSoC experience**

I hope to gain valuable experience from this program related to code testing, development, and documentation in order to improve the available resources for tracking animal behavior data. This mentorship and hands-on experience related to biological coding will benefit my professional goals while helping to contribute open source resources for other scientists in the community.

**Are you also applying to projects with other organisations in GSoC 2025?**

This is the only project and organization I am applying to in GSoC 2025.

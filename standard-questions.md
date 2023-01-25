# DPG Standard Questionary
This document contains the set of questions that are collected in the application form at [app.digitalpublicgoods.net](https://app.digitalpublicgoods.net/form) and used to assess each of the indicators set forth in the DPG Standard.

## GENERAL INFORMATION
About your digital solution

__Solution name__
<br>Please enter the full name of your digital solution. This will be listed on the registry if your application is accepted.

__Aliases (if any)__
<br>Please mention any acronyms or aliases used to refer to your digital solution. Use commas to enter multiple names.

__Solution category__
<br>Please select one or more of the four categories that your digital solutions belong to (Most solutions belong to only one category)
* Open Software
* Open Content
* Open Data
* Open AI Model

__Short description__
<br>Please write a tweet-length description of the solution. If your application is approved, this will be reflected on the public DPG registry.

__Website__
<br>Please provide link(s) to the website or webpage of your digital solution.

__Where is the solution’s code repository?__
<br>Please provide link(s) to your code repo that exposes source code. This is mandatory if your solution is an Open Software solution.

<table>
    <thead>
        <tr>
            <th width="25%">Indicator: </th>
            <th width="25%">Description:</th>
            <th width="50%">DPG Standard Assessment Questions:</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td valign="top">1. SDG Relevance</td>
            <td valign="top">Your digital solution must demonstrate relevance to one or more <a href="https://sdgs.un.org/goals" target="_blank">Sustainable Development Goals</a>
            </td>
            <td valign="top">
                <ul>
                    <li>Which SDGs is your solution relevant to?*</li>
                    <li>How is your solution relevant to each SDG you’ve selected above?* <br>Please provide information and/or link(s) to a webpage, article or documentation that adequately demonstrates relevance to each SDG selected above. Solutions that fail to do so will be out rightly rejected without a second chance for providing additional information or clarifications.
                </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">2. Open Licensing</td>
            <td valign="top">Your digital solution must use an approved open license.
            </td>
            <td valign="top">
                <ul>
                    <li>Which open license(s) is/are used by your solution? <br>Please <a href="https://github.com/DPGAlliance/publicgoods-candidates/blob/main/help-center/licenses.md" target="_blank">refer here for the list of approved open licenses</a> accepted. (If you do not currently use one of the approved licenses, your solution cannot be approved as a DPG)
                    </li>
                    <li>Provide evidence of use of the selected open license(s).* <br>Please provide link(s) to public pages where the license(s) selected above are hosted for this project. This could be a license file in GitHub repository or a public URL on the project website.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">3. Clear Ownership</td>
            <td valign="top">The organisation that owns this digital solution must be clearly defined.</td>
            <td valign="top">
                <ul>
                    <li>Who owns this digital solution?* <br>If there is no formal organization associated with the solution, please enter names of the people who own this solution.
                    </li>
                    <li>Provide evidence(s) of ownership.*<br>Please provide link(s) to the copyright, trademarks, or publicly available ownership documentation for the digital solutions. It could be a webpage that clearly defines who owns the digital solution. Terms of Service may also indicate the ownership of the digital solutions. Additional legal documentation that provides supporting information will strengthen your application. Digital solutions owned by a parent organisation, could highlight the digital solutions on their website to strengthen the application.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">4. Platform Independence</td>
            <td valign="top">If your digital solution has any mandatory dependencies that create more restrictions than the original license, then there should be open alternatives so that such dependencies can be replaced with the alternatives without making significant changes to the core digital solution.</td>
            <td valign="top">
                <ul>
                    <li>Does this solution use any closed components that create proprietary dependency?* <br>Yes or No. You will be required to answer the next question if you select Yes.
                    </li>
                    <li>How can these closed component(s) be replaced with open alternative(s)? <br>Please provide a list of the active open alternatives for the closed component(s) and demonstrate that these close component(s) can be replaced with those open alternatives with minimal configuration changes, without requiring a major overhaul of the entire system. This requirement can be best answered by a technical member of your team. Leave this blank if the above answer is No.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">5. Documentation</td>
            <td valign="top">Your digital solution must have strong documentation. The documentation should allow a technical person unfamiliar with the solution to launch and run the digital solution themselves.</td>
            <td valign="top">
                <ul>
                    <li>Where is your solution’s documentation?*<br>Please summarize how and where the solution is documented along with link(s) to all relevant documents.
                    For software solutions, documentation could include an open repo, technical specifications, functional requirements, etc.
                    For data sets or solutions, documentation could describe all the fields in the set, and provide context on how the data was collected and how it should be interpreted.
                    For content, documentation could include relevant compatible apps, software, hardware required to access the content and any instructions on how to use it. For more details on documentation best practices, please visit this <a href="https://github.com/DPGAlliance/publicgoods-candidates/blob/main/help-center/documentation.md" target="_blank">link</a>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">6. Non-PII Data Extraction</td>
            <td valign="top">If your solution collects or uses non-PII data and/or content, then there must be mechanisms for extracting or importing non-PII data from or into the system in a non-proprietary format.</td>
            <td valign="top">
                <ul>
                    <li>Does your solution collects or uses non-PII data and/or content?* <br> Yes or No. You will be required to answer the next question only if you collect or use non-PII data and/or content.
                    </li>
                    <li>Describe the mechanism for extracting or importing non-PII data from or into the system in a non-proprietary format. <br> Please provide a detailed description of how the non-PII data can be imported or exported into non-proprietary formats such as CSV/XML/JSON etc or via exposing the non-PII data through APIs.
                    </li> 
                </ul>
            </td>
        </tr>
        <tr>
            <td colspan="3" style="background-color:lightgrey">
                Note that requirements related to indicators 7-9 can only be answered by someone authorized to speak on behalf of the project.
            </td>
        </tr>
          <tr>
            <td valign="top">7. Privacy & Applicable Laws</td>
            <td valign="top">Your digital solution must comply with relevant privacy, domestic and other applicable international laws.</td>
            <td valign="top">
                <ul>
                    <li>Provide a list of relevant privacy, domestic and other applicable international laws your solution complies with.* <br>Please enter a list of the relevant laws that your digital solutions complies with such as General Data Protection Regulation (GDPR), Indian IT Act, Persons with Disabilities Act 2020, Canadian Disabilities Act, Americans with Disabilities Act of 1990, etc.</li>
                    <li>Provide evidence(s) of adherence with the laws mentioned above.*<br>Please provide link(s) to the privacy policy, terms of service or other relevant legal documentation as demonstrate adherence</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">8. Open Standards & Best Practices</td>
            <td valign="top">Your digital solution must comply with relevant standards, best practices and/or principles.</td>
            <td valign="top">
                <ul>
                    <li>Provide a list of the open standards your solution adheres to and demonstrate adherence.* <br>You may provide link(s) to a validator, open test suite, etc to demonstrate adherence. Here is a list of <a href="https://github.com/DPGAlliance/publicgoods-candidates/blob/main/help-center/open-standards.md" target="_blank">open standards</a> that you may find helpful.
                    </li>
                    <li>Provide a list of best practices & principles your solution adheres to and demonstrate adherence.* <br>You may provide link(s) to a validator, open test suite, etc to demonstrate adherence. Here is a list of <a href="https://github.com/DPGAlliance/publicgoods-candidates/blob/main/help-center/best-practices.md" target="_blank">best practices</a> that you may find helpful.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">9 A. Data Privacy & Security</td>
            <td valign="top">If your digital solution collects, stores and distributes PII data (personally identifiable information) data, then you must demonstrate how is the privacy, security and integrity of this data is ensured
            </td>
            <td valign="top">
                <ul>
                    <li>Does your solution collect / store / distribute PII data?*<br>Please select the option that is applicable for your solution. <br>PII data is NOT collected NOT stored and NOT distributed. <br>PII data is collected but NOT stored and NOT distributed. <br>PII data is collected and stored but NOT distributed. <br>PII data is collected and stored and distributed.
                    </li>
                    <li>What are types of data that is collected / stored / distributed?<br>Please list the types of PII data. Example: Name, Email, etc.</li>
                    <li>How does your solution ensures data privacy & security?<br>Please demonstrate how the project ensures the privacy, security and integrity of this data and the steps taken to prevent adverse impacts resulting from its collection, storage and distribution.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">9 B. Inappropriate & Illegal Content</td>
            <td valign="top">If your digital solution collects, stores and distributes content, then you must have policies identifying inappropriate and illegal content such as child sexual abuse materials in addition to processes for detecting, moderating, reporting and removing inappropriate/ illegal content.
            </td>
            <td valign="top">
                <ul>
                    <li>Does your solution collect / store / distribute content?*<br>Please select the option that is applicable for your solution. <br>Content is NOT collected NOT stored and NOT distributed. <br>Content is collected but NOT stored and NOT distributed. <br>Content is collected and stored but NOT distributed.<br>Content is collected and stored and distributed.
                    </li>
                    <li>What are the types of content that is collected / stored / distributed?<br>Please list the types of content.
                    </li>
                    <li>How does your solution handles inappropriate and illegal content?<br>Please describe (1) the policies for identifying inappropriate and illegal content and (2) the processes for detecting, moderating, reporting and removing inappropriate / illegal content. Please include the average response time for assessment and/or action. Please describe how the mechanism for identifying, reporting and removing innapropriate/illegal content, achieves those goals without compromising any expectations of privacy and integrity that individual creators of legal content will have.
                    </li>
                </ul>
            </td>
        </tr>
         <tr>
            <td valign="top">9 C. Protection from Harassment</td>
            <td valign="top">If your digital solution facilitates interactions with or between users or contributors there must be a process for users and contributors to protect themselves against grief, abuse, and harassment. The project must have system(s) to address the safety and security of underage users
            </td>
            <td valign="top">
                <ul>
                    <li>Does your solution facilitate interactions with or between users and/or contributors?*<br>Yes or No. Please select the option that is applicable for your solution. You will be required to answer the next question if you select Yes.
                    </li>
                    <li>How does your solution enables users and contributors to protect themselves from harassment? <br>Please describe (1) policies such as a code of conduct and processes users and contributors can use to protect themselves and (2) processes that addresses the safety and security of underage users.
                    </li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>


**Scale of Solution:** 
<br>Additional information highlighting the extent and scale of your solution's implementation and success. 
* Where was this solution developed?*: _Please select one or more countries._
* Where is this solution actively deployed?*: _Please select one or more countries._
* Are there any multi-lateral organisations using your solution?: _Please select from the options below._

# Requirements Document

## 1. Look and Feel

- **ID#:** 1
- **Type:** Look and feel
- **Description:** The system should have an intuitive and visually appealing interface that conveys a sense of trust and safety.
- **Rationale:** A welcoming design will contribute to a positive user experience and foster a sense of security among parents and volunteers.
- **Fit Criterion:** Users find the interface visually appealing in usability tests.
- **Priority:** High
- **Dependencies:** 15 (Appearance), 16 (Learning)

## 2. Personalization

- **ID#:** 2
- **Type:** Personalization
- **Description:** The system should allow for personalized information input by parents and provide tailored outputs based on their preferences.
- **Rationale:** Personalization enhances user experience, making the check-in/check-out process more efficient for both new and returning families.
- **Fit Criterion:** Users can successfully input and retrieve personalized information.
- **Priority:** High
- **Dependencies:** 3 (Ease of Use)

## 3. Ease of Use

- **ID#:** 3
- **Type:** Ease of Use
- **Description:** The system should be user-friendly, minimizing the time and effort required for parents and volunteers to complete the check-in/check-out process.
- **Rationale:** A straightforward system reduces stress for both users and ensures a positive interaction with the technology.
- **Fit Criterion:** Completion of the check-in/check-out process of users.
- **Priority:** High
- **Dependencies:** None

## 4. Accessibility

- **ID#:** 4
- **Type:** Accessibility
- **Description:** The system should look and operate the same on all devices.
- **Rationale:** Not all users know how to use or have access to the operating system the project is built on.
- **Fit Criterion:** Ensure compatibility of across various platforms.
- **Priority:** High
- **Dependencies:** None

## 5. Speed and Latency

- **ID#:** 5
- **Type:** Speed and Latency
- **Description:** The system should have minimal latency and provide a speedy check-in/check-out experience.
- **Rationale:** Quick processing contributes to overall efficiency, reducing wait times for parents and ensuring a smooth operation.
- **Fit Criterion:** Check-in and check-out processes are completed within a timely manner
- **Priority:** High
- **Dependencies:** None

## 6. Robustness

- **ID#:** 6
- **Type:** Robustness
- **Description:** The system should be resilient, capable of handling unexpected errors and recovering gracefully.
- **Rationale:** A robust system minimizes disruptions and ensures continuous functionality, especially during peak times.
- **Fit Criterion:** System recovers after encountering errors.
- **Priority:** Medium
- **Dependencies:** None

## 7. Scalability

- **ID#:** 7
- **Type:** Scalability
- **Description:** The system should scale seamlessly to accommodate an increasing number of users and data.
- **Rationale:** Scalability ensures the system remains effective as the number of families and children grows.
- **Fit Criterion:** The system can handle an increase in usage without performance degradation.
- **Priority:** Medium
- **Dependencies:** None

## 8. Longevity

- **ID#:** 8
- **Type:** Longevity
- **Description:** The system should be designed for long-term use, considering future updates and technological advancements.
- **Rationale:** A long-lasting system reduces the need for frequent replacements, ensuring stability and consistency.
- **Fit Criterion:** The system remains compatible with new technologies.
- **Priority:** Medium
- **Dependencies:** None

## 9. Privacy

- **ID#:** 9
- **Type:** Privacy
- **Description:** The system should adhere to privacy regulations, protecting the confidentiality of user information.
- **Rationale:** Ensuring privacy builds trust with parents who entrust their children's information to the system.
- **Fit Criterion:** No unauthorized access to user data during a simulated security audit.
- **Priority:** High
- **Dependencies:** 18 (Audit)

## 10. Capacity

- **ID#:** 10
- **Type:** Capacity
- **Description:** The system should handle the capacity of all families and children within the church community.
- **Rationale:** Adequate capacity ensures the system remains effective as the church community grows.
- **Fit Criterion:** The system can accommodate up to 500 families and 1000 children simultaneously.
- **Priority:** Medium
- **Dependencies:** 7 (Scalability)

## 11. Authentication

- **ID#:** 11
- **Type:** Authentication
- **Description:** The system should implement secure authentication methods to prevent unauthorized access.
- **Rationale:** Ensuring secure access protects sensitive information and maintains trust with users.
- **Fit Criterion:** Successful implementation password policies and SQL security.
- **Priority:** High
- **Dependencies:** 9 (Privacy)

## 12. Localization

- **ID#:** 12
- **Type:** Localization
- **Description:** The system is designed to support one church community at this time.
- **Rationale:** Keeping the system small ensures the systems is compatible for other uses later.
- **Fit Criterion:** Keeping it small will help the families and volunteers feel more secure in the usage.
- **Priority:** Medium
- **Dependencies:** 17 (Internationalization)

## 13. Data Consumption Limits

- **ID#:** 13
- **Type:** Data consumption limits
- **Description:** The system should efficiently manage data usage to avoid exceeding limits.
- **Rationale:** Efficient data management ensures cost-effectiveness and optimal system performance.
- **Fit Criterion:** Data consumption remains within allocated limits during a month-long test with 1000 families.
- **Priority:** Medium
- **Dependencies:** None

## 14. Understandability

- **ID#:** 14
- **Type:** Understandability
- **Description:** The system should present information in a clear and understandable manner for both parents and volunteers.
- **Rationale:** Clarity reduces the chance of errors and ensures a smooth user experience.
- **Fit Criterion:** Users can accurately interpret the information presented during the check-in/check-out process.
- **Priority:** High
- **Dependencies:** 1 (Look and Feel)

## 15. Appearance

- **ID#:** 15
- **Type:** Appearance
- **Description:** The system's visual design should be inviting and align with the church's ethos.
- **Rationale:** A visually appealing design contributes to a positive first impression, fostering trust and engagement.
- **Fit Criterion:** Users find the visual design inviting in usability tests.
- **Priority:** High
- **Dependencies:** None

## 16. Learning

- **ID#:** 16
- **Type:** Learning
- **Description:** The system should facilitate a short learning curve for both parents and volunteers.
- **Rationale:** Minimizing the learning curve enhances user adoption and overall satisfaction.
- **Fit Criterion:** Users can complete the check-in/check-out process without assistance after using the system once.
- **Priority:** High
- **Dependencies:** None

## 17. Internationalization

- **ID#:** 17
- **Type:** Internationalization
- **Description:** The system should individual to the church.
- **Rationale:** Keeping it small will allow system to be refined before offering it to other churches.
- **Fit Criterion:** Users will be able to use the system on the churches computers and users personal devices.
- **Priority:** Low
- **Dependencies:** None

## 18. Audit

- **ID#:** 18
- **Type:** Audit
- **Description:** The system should undergo regular security audits to identify and address vulnerabilities.
- **Rationale:** Regular audits enhance the system's overall security, safeguarding user data.
- **Fit Criterion:** Successful completion of a security audit without major vulnerabilities.
- **Priority:** High
- **Dependencies:** None

## 19. Extensibility

- **ID#:** 19
- **Type:** Extensibility
- **Description:** The system should be designed to allow for future updates and additional features.
- **Rationale:** An extensible system ensures adaptability to changing requirements and technological advancements.
- **Fit Criterion:** New features can be added without significant rework of the existing system.
- **Priority:** Medium
- **Dependencies:** None

## 20. Reliability

- **ID#:** 20
- **Type:** Reliability
- **Description:** The system should consistently perform its intended functions without unexpected failures.
- **Rationale:** Reliability is crucial to maintaining trust with users and ensuring a smooth operation.
- **Fit Criterion:** The system operates without unexpected failures.
- **Priority:** High
- **Dependencies:** None

## 21. Automated Assignment

- **ID#:** 21
- **Type:** Functionality
- **Description:** The system should automatically assign classrooms based on the information provided during check-in.
- **Rationale:** Automated assignment streamlines the process and reduces the workload on volunteers.
- **Fit Criterion:** Automated classroom assignments.
- **Priority:** High
- **Dependencies:** 2 (Personalization)

## 22. QR Code Integration

- **ID#:** 22
- **Type:** Functionality
- **Description:** QR codes should be integrated for quick and efficient check-in/check-out.
- **Rationale:** QR codes expedite the process, enhancing user convenience.
- **Fit Criterion:**  High success rate in QR code scans.
- **Priority:** High
- **Dependencies:** None

## 23. Email Notifications

- **ID#:** 23
- **Type:** Functionality
- **Description:** The system should send email notifications with check-in details and barcode for check-out.
- **Rationale:** Email notifications provide an additional option for parents and a backup for check-out.
- **Fit Criterion:** Emails sent within minutes of completing check-in.
- **Priority:** Low
- **Dependencies:** None

## 24. Volunteer Assistance

- **ID#:** 24
- **Type:** Functionality
- **Description:** Volunteers should be available to assist parents who encounter issues during check-in/check-out.
- **Rationale:** Volunteer assistance ensures a smooth process for all users, even those unfamiliar with technology.
- **Fit Criterion:** User issues addressed by volunteers within minutes.
- **Priority:** Low
- **Dependencies:** 3 (Ease of Use)

## 25. Tag Printing Options

- **ID#:** 25
- **Type:** Functionality
- **Description:** Parents should have the option to choose between hard tags and electronic tags (email) for check out.  Tags for children during check-in should always be printed.
- **Rationale:** Providing options caters to different preferences and scenarios.
- **Fit Criterion:** Parents successfully choose their preferred tag option.
- **Priority:** High
- **Dependencies:** 28 (Functionality)

## 26. Real-time Reporting

- **ID#:** 26
- **Type:** Functionality
- **Description:** The system should provide real-time reports on attendance and other relevant metrics.
- **Rationale:** Real-time reporting assists in tracking attendance and enables better planning.
- **Fit Criterion:** Attendance reports can be access upon request.
- **Priority:** Low
- **Dependencies:** None

## 27. Tag Printing Accuracy

- **ID#:** 27
- **Type:** Functionality
- **Description:** The system should print proper name and other relevant information on child/children tags.
- **Rationale:** Assists volunteers in case a student wanders from classroom or if student has food alergy.
- **Fit Criterion:** Can quickly contact parents in case of emergency.
- **Priority:** High
- **Dependencies:** 21 (Functionality), 28 (Functionality)

## 28. User Data Input

- **ID#:** 28
- **Type:** Functionality
- **Description:** The system should facilitate easy and accurate input of parent and child information during check-in. The system should store data for easy access for returning families.
- **Rationale:** Streamlined data input ensures the system captures necessary information efficiently.
- **Fit Criterion:**  Accuracy in data input during check-in.
- **Priority:** High
- **Dependencies:** 2 (Personalization), 3 (Ease of Use)
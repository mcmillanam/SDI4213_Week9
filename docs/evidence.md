# Week 9 Screenshot Evidence

Insert or paste your screenshots into your submitted document and label them exactly as follows:

1. Milestone 1 - Verified that the Help Desk application successfully starts with Docker Compose and that the required services are running.
   <img width="896" height="155" alt="Milestone 1 Screenshot" src="https://github.com/user-attachments/assets/84e0b62a-0f86-4f52-82c0-87b64c173c7a" />

2. Milestone 2 - Verified that the .env file is ignored by Git and does not appear as a tracked file, helping prevent sensitive configuration information from being committed to the repository.
   <img width="887" height="179" alt="Milestone 2 Screenshot" src="https://github.com/user-attachments/assets/15e5278f-fb5b-46a1-8cea-741eb30c8dfb" />

3. Milestone 3 - Configured Dependabot in GitHub to monitor Python dependencies and GitHub Actions dependencies on a weekly schedule.
   <img width="2479" height="738" alt="Milestone 3 Screenshot" src="https://github.com/user-attachments/assets/8354526c-adb6-49b2-b84f-1b462b485f51" />

4. Milestone 4 - Docker Scout identified 98 vulnerabilities across 19 packages in the baseline Help Desk image, including 5 critical, 42 high, 23 medium, and 28 low vulnerabilities.
   <img width="512" height="236" alt="Milestone 4 Screenshot" src="https://github.com/user-attachments/assets/4d49defb-74ab-4927-bbc3-3b4180312c9c" />

5. Milestone 5 - Docker Scout analyzed an SBOM containing 189 packages and identified python:3.13-slim as the current base image. It recommended alternative images, including Alpine, which could reduce base-image vulnerabilities and image size. 
   <img width="956" height="1082" alt="Milestone 5 Screenshot" src="https://github.com/user-attachments/assets/7aa3cd4a-70a0-4fee-995c-3c40959b259f" />

6. Milestone 6 - Hardened the Help Desk Dockerfile by creating a dedicated non-root application user and configuring the container to execute under that account rather than root.
   <img width="781" height="432" alt="Milestone 6 Screenshot" src="https://github.com/user-attachments/assets/2e765ff5-f80b-493e-bd2a-0d1104b2d8f9" />

7. Milestone 7 - Verified that the hardened Help Desk Docker image executes under a non-root user by confirming that its runtime UID is 10001 instead of 0.
   <img width="869" height="311" alt="Milestone 7 Screenshot" src="https://github.com/user-attachments/assets/d60696ed-b4be-4e0b-b658-1bb2ce3ac74f" />

8. Milestone 8 - Created a GitHub Actions security workflow that checks whether the .env file is tracked by Git, builds the hardened Docker image, and verifies that the container runs as a non-root user.
   <img width="1128" height="1228" alt="Milestone 8 Screenshot" src="https://github.com/user-attachments/assets/96d90c70-512f-4db3-b1bd-6587e708a962" />

9. Milestone 9 - Verified that the GitHub Actions security workflow successfully checks that .env is not tracked by Git and that the hardened Docker container runs as a non-root user.
    <img width="1168" height="1246" alt="Milestone 9 Screenshot" src="https://github.com/user-attachments/assets/64db7d41-6fbf-483a-a153-1997390a6b0a" />

10. Milestone 10 - Completed the final security review of the Week 9 pull request, confirming that the required security configuration files were included and that both CI and security checks passed successfully.
    <img width="1161" height="1236" alt="Milestone 10 Screenshot" src="https://github.com/user-attachments/assets/17ba355d-1638-4017-b3a2-c209e659efb9" />


Do not include passwords, tokens, API keys, or other secrets in screenshots.

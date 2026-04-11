## Privacy Policy — Auto Blackboard Downloader

**Effective date:** April 12, 2026

Auto Blackboard Downloader (“the Extension”, “we”, “our”) helps users download course files from Blackboard into a ZIP file.

### 1. Single Purpose
The Extension’s single purpose is to let the user download course materials from Blackboard course pages.

### 2. Data We Handle
To provide this feature, the Extension may handle:

- Blackboard course content and resource URLs that the user accesses while using Blackboard
- File metadata needed for ZIP creation (for example: file names, folder paths, content IDs)
- Blackboard account email address extracted from the user’s profile page, used only for subscription verification
- Technical request/response data needed to resolve signed download links

### 3. What We Collect and Why
We only process data necessary to provide the download feature:

- **Course/resource URLs and file metadata:** used to discover and download files selected by the user
- **Profile email address:** sent to our verification endpoint to check subscription entitlement
- **Signed file URLs:** used transiently to download requested files

We do not collect data for advertising, profiling, or unrelated analytics.

### 4. Host Access (Minimum Necessary)
Host access is limited to the minimum domains required for functionality:

- `https://blackboard.cuhk.edu.hk/*`  
  Used for Blackboard course content, Learn API endpoints, and profile email extraction.
- `https://*.blackboardcdn.com/*`  
  Used for signed file download URLs.
- `https://autobbapi.kalalib.com/*`  
  Used only for subscription verification requests.

No broad or unrelated host access is requested.

### 5. Permissions and Use
The Extension requests only required permissions for current functionality:

- `webRequest`  
  Used to observe redirect behavior and resolve Blackboard signed download links needed for file download.

The Extension does not request unnecessary permissions such as broad tab access or runtime script injection permissions.

### 6. Data Sharing and Transfers
We do not sell personal data.

Data is only transferred when required to provide the Extension’s single purpose, including:

- Subscription verification request to `autobbapi.kalalib.com` (email and verification context)
- File/resource requests to Blackboard and Blackboard CDN for user-initiated downloads

No transfer is made for personalized ads, retargeting, or data brokerage.

### 7. Limited Use Commitments
Consistent with Chrome Web Store User Data Policy:

- **Allowed use:** only to provide/improve the download feature
- **Allowed transfer:** only when necessary for that feature, legal compliance, or security
- **Prohibited advertising:** no personalized/interest-based ad use
- **Prohibited human interaction:** no human review of user data except where required by law, security, or user-requested support with explicit consent

### 8. Data Retention
Downloaded files are created locally for the user.  
Operational data is handled only as long as needed for the request flow and troubleshooting.  
We do not intentionally retain personal data longer than necessary for service delivery and compliance.

### 9. Security
Personal or sensitive user data is transmitted over secure connections (HTTPS).  
We apply reasonable technical and organizational safeguards appropriate to the data processed.

### 10. User Controls
Users control use of the Extension by:

- Installing/removing the Extension
- Controlling when downloads are initiated
- Revoking Extension permissions through Chrome settings

### 11. Children
The Extension is not directed to children and is intended for users of Blackboard course platforms.

### 12. Changes to This Policy
We may update this Privacy Policy as functionality or legal requirements change. The updated effective date will be shown at the top.

### 13. Contact
For privacy questions or requests, contact:  
contact@kalalib.com
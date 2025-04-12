# Test_doc_Prep
 **Product Requirements Document (PRD)**
Title: Vulnerability Scanner for Container Images
Problem Statement 1: Product Requirement and Low-Fidelity Wireframes

**1. User Goals**
    > View which container images have vulnerabilities.
    > Understand the severity (Critical, High, Medium, Low) of these vulnerabilities.
    > Quickly identify which images need immediate action (Critical/High).
    > Easily search, filter, and sort through thousands of images.
    > Take action on vulnerabilities (e.g., updating a base image or dependency).
    
**2. Image List View**
    > Tabular view of all scanned images with:
        > Image name and tag
        > Last scanned date
        > Vulnerability summary (Critical/High counts)
        > Fix available indicator (Yes/No)
        
**3. Filters and Search**
    > Filter by:
        > Severity (e.g., show only Critical/High)
        > Image name/tag
        > Fix availability
    > Search by image name or CVE ID.
    > Sort by scan date, severity, or image name

**4. Image Detail View**
    > When clicking on an image:
        >Full list of vulnerabilities with:
            > CVE ID
            > Severity level
            > Affected component/package
            > Installed version
            > Fix version (if available)
            >Description and reference links

**3. Fix Recommendations**
    > Show remediation advice:
        > Upgrade base image
        > Patch library version

**6. Export/Reporting**
    > Download scan results as:
        > CSV
        > PDF
        
**7. Notifications (Optional/Future)**
    > If we want to get email alert when new critical vulnerabilities are found we should intigrate with email.
    
**8. Success Metrics**
    >Time taken to identify critical vulnerabilities reduced by 50%
    > 90% of users can locate and filter affected images within 2–3 clicks
    > At least 80% of scanned images show recommended remediations
    > Product uptime ≥ 99.9%




            

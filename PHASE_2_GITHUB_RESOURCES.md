# Phase 2: GitHub & Degree-Path Resources for Jamaican Universities

## Jamaica-Focused GitHub Tools

### 1. **Jamaica Workforce Accelerator** (terrasample/rolerocket-ai)
- **Purpose:** Career pathway & skills development for Jamaica job market
- **Use:** Maps degree programs to actual Jamaican companies and jobs
- **Sectors Covered:** IT, Education & Training, Business Services, Finance
- **Companies Tracked:** Teleperformance Jamaica, Sutherland Jamaica, IBEX Jamaica
- **Key Feature:** Links university degrees → actual employment opportunities in Jamaica
- **URL:** https://github.com/terrasample/rolerocket-ai
- **Relevance:** Help students understand what jobs they can get with their degree

### 2. **Degree Path & Course Demand Planner** (typicaleoxx/grad-path)
- **Purpose:** Plan courses, check prerequisites, estimate workload by semester
- **Use Cases:**
  - Students create 4-year graduation plan
  - Check if prerequisites are met before registering
  - See recommended course sequence
  - Estimate study hours per course per semester
  - Generate graduation timeline reports
- **Features:**
  - Prerequisite validation
  - Workload estimation
  - Multi-semester planning
  - Graduation progress tracking
  - Priority course lists
- **Input Format:** CSV files (university course data)
- **Output Format:** Course demand reports, graduation timelines
- **URL:** https://github.com/typicaleoxx/grad-path
- **Relevance:** Directly applicable to UTech, UWI, or Mico universities

---

## Caribbean Examinations Council (CXC) Resources

### **CSEC** (Caribbean Secondary Education Certificate)
- **Purpose:** Secondary completion qualification
- **For University Entry:** Grades I-III required
- **Recognition:** Across Caribbean universities (UWI, UG)
- **URL:** https://www.cxc.org/csec
- **Subjects:** Aligned with Caribbean curricula

### **CAPE** (Caribbean Advanced Proficiency Examination)
- **Purpose:** Post-secondary qualification (for university entry/progression)
- **Unit System:** Six CAPE Units = UWI admission
- **International Recognition:** Equivalent to UK A-Levels
- **US Recognition:** Credits/exemptions offered at US universities
- **URL:** https://www.cxc.org/cape
- **Key Subjects for Common Programs:**
  - Engineering: Mathematics, Physics, Chemistry
  - Medical: Chemistry, Biology, Mathematics
  - Business: Economics, Accounting, Management of Business

---

## Degree Path Resources by Program

### Engineering (UTech)
- **Relevant Tools:** grad-path for course planning
- **CXC Prep:** CAPE in Physics, Mathematics, Chemistry
- **Specializations:** Civil, Mechanical, Electrical, Electronics
- **Practicum:** Work-integrated learning component tracked in grad-path
- **Job Connections:** Jamaica Workforce Accelerator (manufacturing, infrastructure sectors)

### Medical/Health Sciences (UWI)
- **Relevant Tools:** grad-path for rigorous prerequisite tracking
- **CXC Prep:** CAPE Chemistry, Biology, Mathematics
- **Program Length:** 5-6 years typical
- **Registration Portal:** UWI SAS system
- **Regional Alignment:** Caribbean health curricula through CXC

### Business & Management (UTech COBAM)
- **Job Market:** Jamaica Workforce Accelerator shows finance/management employers
- **CXC Prep:** Economics, Accounting, Business Management
- **Skills:** Aligned to professional certification pathways (CPA, MBA)
- **Career Focus:** Direct pathway to Jamaican company employment

### Architecture (UTech - Only in English-Speaking Caribbean)
- **Program Length:** 5 years integrated
- **Practicum Requirements:** Significant architectural internships
- **CXC Prep:** Mathematics, Technical Drawing, Design
- **Specializations:** Building design, sustainable architecture, urban planning

### Computer Science & IT (UTech, UWI)
- **Job Market:** Jamaica Workforce Accelerator tracks IT employers
- **CXC Prep:** Information Technology, Mathematics
- **Industry Certifications:** CompTIA, AWS, Google Cloud aligned with curriculum
- **Employment Focus:** IT services companies in Kingston and nationwide

### Teacher Education (Mico, Shortwood, NCU)
- **CAPE Subjects:** Relevant to teaching specialization
- **Program Focus:** Early childhood, primary, secondary, special education
- **Practicum:** School-based teaching placements
- **Regional Standards:** CXC teacher education frameworks

---

## Course Planning Tools

### grad-path Capabilities
**For Students:**
- Create 4-year degree plan
- See prerequisite requirements
- Check time conflicts
- Estimate study hours per semester
- Track graduation progress

**For Advisors/Departments:**
- Generate course demand forecasts
- Identify bottleneck courses
- Create priority registration lists
- Plan course scheduling

**Data Format:**
- Input: CSV files with student records, courses, prerequisites
- Output: Graduation timelines, priority lists, demand reports

**Installation:**
```
git clone https://github.com/typicaleoxx/grad-path
pip install -r requirements.txt
python src/planner.py
```

---

## Skill Development & Career Resources

### Jamaica Workforce Accelerator Features
- Sector mapping (IT, education, finance, business services)
- Company profiles and career paths
- Location-based employment data
- Skills alignment to degrees
- Career advancement pathways

### Industry Certifications by Field
- **Computing:** CompTIA Security+, AWS Solutions Architect, Google Cloud Associate
- **Business:** CPA (Chartered Public Accountant), Project Management Professional
- **Healthcare:** NCLEX (nursing), Medical Board Exams
- **Teaching:** Caribbean Teacher Certification standards

### Online Learning Platforms
- **Coursera:** Professional certificates in engineering, business, data science
- **LinkedIn Learning:** Jamaica-focused career development courses
- **FutureLearn:** Health, development, and education courses

### Internship & Practicum Planning
- grad-path tracks practicum courses alongside theory
- Work-integrated learning component mappable for all programs
- Employer connection through Jamaica Workforce Accelerator

---

## Caribbean Education Standards

### CXC Learning Framework
- **CSEC:** Six-point grading system (Grades I-VI)
- **CAPE:** Seven-point grading for units
- **Assessment:** Terminal exams + School-Based Assessment (SBA)
- **Consistency:** Standardized across Caribbean

### Regional Accreditation
- **UWI Recognition:** Bachelor's degrees recognized in North America, Europe, Caribbean
- **CARICOM Frameworks:** Ensure education consistency
- **International Transfer:** Credits recognized by partner universities

---

## Course Registration & Scheduling Tools

### GitHub Scheduling Tools (Transferable)
- **My Timetable Premium:** Conflict detection for class schedules
- **HMRITM-app:** Academic calendar and timetable display
- **sogrim:** Grade tracking + schedule planner with exam clash detection

### UTech/UWI Integration Potential
- Most Jamaica institutions use CSV-compatible systems
- grad-path can export schedules in standard formats
- Scheduling tools can integrate with university portals

---

## What's NOT Available Yet

**Missing on GitHub:**
- Degree requirement databases for UWI Mona programs
- Degree requirement databases for UTech specializations
- Course review repositories from Jamaican students
- Curriculum comparison tools for Caribbean universities
- Student forum archives about registration experiences

**Recommendation:** Create local GitHub repos with:
1. UWI degree requirements by faculty
2. UTech program curricula by college
3. Course descriptions and prerequisites
4. Student resources and study guides

---

## Integration Strategy

### For Your Friend's Immediate Need:
1. Use grad-path to plan her degree
2. Reference Jamaica Workforce Accelerator for career outcomes
3. Check CXC standards for prerequisite alignment

### For Building a Comprehensive Tool:
1. Adopt grad-path as foundation
2. Add Jamaica university data (CSV format)
3. Integrate workforce accelerator API
4. Build custom student portal

### Long-term:
1. Create GitHub repo with Jamaican university data
2. Build web interface for drag-and-drop planning
3. Add student forum/resources
4. Integrate with university registration portals

---

## Key GitHub Repositories Summary

| Repository | Purpose | Relevance | Status |
|------------|---------|-----------|--------|
| terrasample/rolerocket-ai | Career pathways | Jamaica-specific jobs | Active |
| typicaleoxx/grad-path | Course planning | Degree planning tool | Active |
| awesome-courses | General education | Foundation reference | Maintained |
| My Timetable Premium | Schedule planning | Conflict detection | Active |

---

**Compiled:** September 2, 2026
**Sources:** GitHub API, CXC.org, Caribbean education documentation
**Status:** Phase 2 research complete


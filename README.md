# data-projects
Non-programmatic projects for data analysis from various sources such as XLS files, CSV, or SQL using advanced tools like Power BI, MS Project, Alteryx, and SSIS.
# p1:
  # Overview
      This project leverages Power BI to analyze financial and geographic data for companies based in the United States. The analysis focuses on price distribution        across different states, sectors (based on GICS - Global Industry Classification Standard), and headquarters locations of various companies.

  # Key Features:
      * Price Analysis by State: Visualizes price distribution across U.S. states, highlighting key contributors such as California, New York, and Texas.
      * GICS Sector Analysis: Breaks down data by GICS sectors, with a focus on major sectors such as Information Technology, Health Care, and Industrials.
      * Headquarters Location Mapping: Displays the locations of company headquarters and links them to pricing analysis at the state level.
      * Interactive Dashboards: Provides dynamic filters to explore data across different time periods and sectors, allowing for a more in-depth analysis.
  # Tools Used:
      * Power BI: Used for creating data visualizations and interactive dashboards.
      * Data Sources: Aggregated financial data based on state, industry sector, and headquarters locations.
  # Insights:
      * States like California, New York, and Texas lead in total price value contributions.
      * The Information Technology, Consumer Discretionary, and Financial sectors exhibit the highest price accumulations.
      * The interactive dashboard allows users to filter data by specific years and sectors, making it easier to identify trends over time.
# _____________________________________________________________________________________________________________________________________________________________
# _____________________________________________________________________________________________________________________________________________________________
# p2: Data Transformation and Visualization Using Alteryx, SSIS, and Power BI

  # Overview:
       This project focused on analyzing and transforming a dataset related to schools, followed by visualizing the results using Power BI. The dataset included          key information such as school names, enrollment numbers, and full-time teachers. The goal was to apply data transformation techniques using two distinct          tools—Alteryx for the first half and SSIS (SQL Server Integration Services) for the second half—before loading the transformed data into SQL Server                destinations. Finally, a star schema was designed, and visualizations were generated using Power BI to derive insights from the transformed data.

  # Transformation Workflow:

      1. Data Split:
            The dataset was divided into two halves, with the first half processed using Alteryx and the second half using SSIS.
            Each half was further divided into two parts based on a specific filter condition.
      
      2. Data Transformation:
            Applied a filter based on a custom condition.
            Transformed string columns by capitalizing the first letter.
            Split a column (e.g., date) into multiple columns.
            Replaced any whitespace in string columns with underscores.

      3. Destination Loading:
            Data from part 1 of both halves was loaded into the first SQL Server destination.
            Data from part 2 of both halves was loaded into the second SQL Server destination.

  # Star Schema Design: A star schema was designed to support the analysis. It consisted of two dimensions:
      * Dimension 1: School information (name, address, etc.)
      * Dimension 2: Enrollment and teacher details.
      * The fact table held the quantitative metrics such as enrollment numbers and the number of full-time teachers.

  # Visualization in Power BI: 
      After loading the data into the star schema, Power BI was used to generate visual insights:
          * A pie chart visualizing the proportion of student enrollment across different schools.
          * A bar chart displaying the distribution of full-time teachers across schools.
          * Additional charts to highlight other relationships between data points, such as student-to-teacher ratios or school size comparisons.

  # Key Insights: From the visualizations, the following insights can be derived:
      * Schools like Logos Preparatory and Whitby have significantly higher student enrollments.
      * Full-time teachers are more concentrated in specific schools, such as Whitby and Eagle Hill.
      * There are disparities between enrollment numbers and full-time teacher counts, suggesting varying student-teacher ratios across institutions.
# _____________________________________________________________________________________________________________________________________________________________
# _____________________________________________________________________________________________________________________________________________________________
# P3:
  # Overview: 
      This project plan outlines the comprehensive schedule, task breakdown, and resource allocation necessary for the successful creation of a website. It              involves clearly defined milestones, task assignments, and deadlines for each team member involved in the project. The goal is to ensure a streamlined             workflow, optimal resource usage, and timely delivery of each development phase.

  # Key Components:

      1. Resource Allocation:
            Each team member is assigned specific roles and tasks based on their expertise. This includes developers, designers, content creators, and project                 managers.
            Resources have been allocated with clear time frames, ensuring that all team members can collaborate efficiently without delays or bottlenecks.

      2. Task Breakdown:
            The project tasks are broken down into manageable steps such as designing the user interface (UI), developing backend functionalities, content                     creation, and testing.
            Dependencies between tasks are identified to ensure that each phase of development is completed in the correct sequence.

      3. Timeline and Milestones:
            The schedule includes key milestones such as initial planning, design mockups, coding sprints, user testing, and final deployment.
            Each phase has set deadlines, with built-in buffers for review and adjustments if needed.

      4. Team Collaboration:
            Tasks are assigned to individual team members based on their roles, ensuring that everyone has a clear understanding of their responsibilities and                 deadlines.
            Collaboration points are highlighted, such as when designers need to collaborate with developers or when content is required for testing.

      5. Monitoring and Adjustments:
            Regular check-ins and progress reviews are scheduled to ensure the project remains on track.
            Potential risks are accounted for, and contingency plans are in place to handle any unforeseen delays or issues.

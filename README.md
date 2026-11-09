# Krishna Tangudu

**Data Architect at Agilent Technologies · Snowflake Squad 2026 · SAP HANA Distinguished Engineer**

I build enterprise data platforms and share the lessons that help other engineers build them better. My work spans Snowflake architecture, performance, governance and integration, with a growing focus on Cortex Agents and preserving business meaning as data moves between platforms.

From answering SAP HANA community questions to publishing Snowflake code, practical guides and agent evaluations, my approach is consistent: **build, test, explain and help others learn.**

[LinkedIn](https://www.linkedin.com/in/krishna-tangudu-1a961319/) · [DEV articles](https://dev.to/swaroop_krishna_e2f4b83b2) · [Data Platform Field Notes](https://www.linkedin.com/newsletters/data-platform-field-notes-7465407764811452416/) · [Snowflake Community](https://snowflake.discourse.group/u/krishna_tangudu/summary)

## Contributions at a glance

| Contribution | Evidence |
| --- | --- |
| **25 technical articles on DEV** | Practical writing on Snowflake, AI agents, data engineering and platform interoperability; count updated November 9, 2026 |
| **Data Platform Field Notes** | 8 newsletter editions; 860 subscribers as of November 8, 2026 |
| **Four featured public projects** | Snowflake administration agents, Clone++, Salesforce zero-copy integration and the L2P hackathon prototype |
| **Longstanding community support** | SAP Community archive: 1,489 posts, 143 solutions and 385 likes received, checked November 9, 2026 |
| **Speaking and mentoring** | Two SAP Inside Track Top Speaker awards, event organization, technical knowledge sharing and Nvolve mentoring |

## Snowflake projects and practical lessons

### Reusable code and walkthroughs

| Project | Problem addressed and contribution |
| --- | --- |
| [Snowflake Multi-Agent Admin Assistant](https://github.com/LALITHASWAROOPK/agent_snowflake_admin) | Makes account administration, cost analysis and security/governance accessible through Cortex-based agents. Includes setup SQL, semantic views and GitHub Copilot/MCP integration guidance. |
| [Snowflake Clone++](https://github.com/LALITHASWAROOPK/snowflake_cloning) | Addresses the work that follows a database clone: repointing references, recreating streams and managing RBAC. Includes procedures and a four-part technical series. |
| [Salesforce–Snowflake Zero-Copy](https://github.com/LALITHASWAROOPK/salesforce-snowflake-zero-copy) | Shares setup scripts and lessons from data sharing and federation, including V2 enrollment/OIDC, migration checks and the CDC limitations encountered. |
| [L2P — Logic to Product](https://github.com/LALITHASWAROOPK/L2P/tree/l2p-hackathon-build) | Demonstrates how Cortex Agents can turn retrieved business definitions into validated, versioned data products. Built for the October 2026 Intelligence at Work hackathon. |

### Hackathon highlight: preserving meaning, not just moving tables

**L2P** connects a Builder agent that retrieves definitions, creates a candidate and validates it with a Consumer agent that queries the released product through a semantic view. It uses Cortex Search, Cortex Analyst and synthetic HANA, Qlik and Spotfire definitions.

The key demonstration: a many-to-many join produced the expected number of output rows but inflated the sales total. **Contract checks caught the error and blocked release.** A correct candidate passed all eleven checks and was released with versioned evidence.

The repository includes the implementation, demo, architecture and evaluations, with preparation separated from event work. The recorded custom suite passed 19 runs across ten fixed synthetic cases; its scope and unresolved findings are documented alongside the results.

[Watch the demo and inspect the evidence](https://github.com/LALITHASWAROOPK/L2P/blob/l2p-hackathon-build/event/l2p/START-HERE.md) · [Read the case study](https://github.com/LALITHASWAROOPK/L2P/blob/l2p-hackathon-build/event/l2p/submission/L2P-CASE-STUDY.txt)

### Selected writing

These are starting points for readers who want to understand how I investigate problems and share usable lessons:

- **Performance and cost:** [How a Simple Warehouse Resize Saved Us 11% in Daily Credits While Boosting Performance](https://dev.to/swaroop_krishna_e2f4b83b2/how-a-simple-warehouse-resize-saved-us-11-in-daily-credits-while-boosting-performance-2753).
- **Honest platform evaluation:** [Evaluating Adaptive Warehouses for ETL: Why We Reverted to Standard](https://dev.to/swaroop_krishna_e2f4b83b2/evaluating-adaptive-warehouses-for-etl-why-we-reverted-to-standard-239f).
- **Agent reliability:** [My Snowflake Agent Was Wrong. So Was My Evaluation.](https://dev.to/swaroop_krishna_e2f4b83b2/my-snowflake-agent-was-wrong-so-was-my-evaluation-1b46).
- **Interoperability:** [When Zero-Copy and Mirroring Clash: An Iceberg Metadata Gotcha](https://dev.to/swaroop_krishna_e2f4b83b2/when-zero-copy-and-mirroring-clash-an-iceberg-metadata-gotcha-part-3-de3).
- **Business meaning:** [Moving Data Is Easier Than Moving Knowledge](https://dev.to/swaroop_krishna_e2f4b83b2/moving-data-is-easier-than-moving-knowledge-2co4).

<details>
<summary>Explore more technical articles and series</summary>


### Snowflake Deep Dives
- [Same Shared Data. Different Answers. The Snowflake Timezone Trap](https://dev.to/swaroop_krishna_e2f4b83b2/same-shared-data-different-answers-the-snowflake-timezone-trap-20gd)
- [Evaluating Adaptive Warehouses for ETL: Why We Reverted to Standard](https://dev.to/swaroop_krishna_e2f4b83b2/evaluating-adaptive-warehouses-for-etl-why-we-reverted-to-standard-239f)
- [How a Simple Warehouse Resize Saved Us 11% in Daily Credits While Boosting Performance](https://dev.to/swaroop_krishna_e2f4b83b2/how-a-simple-warehouse-resize-saved-us-11-in-daily-credits-while-boosting-performance-2753)
- [From Glue to Horizon: Our Real Journey Building an Iceberg Lakehouse on Snowflake](https://dev.to/swaroop_krishna_e2f4b83b2/iceberg-lakehouse-on-snowflake-journey-3ln4)
- [Understanding Snowflake Virtual Warehouses](https://dev.to/swaroop_krishna_e2f4b83b2/understanding-snowflake-virtual-warehouses-4p5l)
- [How Snowflake's RELY Constraint Supercharges Your Star-Schema Queries](https://dev.to/swaroop_krishna_e2f4b83b2/how-snowflakes-rely-constraint-supercharges-your-star-schema-queries-3n4f)

### Advanced Database Cloning & Administration
- [Part 1: Understanding Snowflake Cloning and why we need Clone++](https://dev.to/swaroop_krishna_e2f4b83b2/part-1-understanding-snowflake-cloning-and-why-we-need-clone-4flk)
- [Part 2: Snowflake Clone++: Repointing Database References and Recreating Streams](https://dev.to/swaroop_krishna_e2f4b83b2/part-2-snowflake-clone-repointing-database-references-and-recreating-streams-3f60)
- [Part 3: Solving Permissions and RBAC in Cloned Databases](https://dev.to/swaroop_krishna_e2f4b83b2/part-3-solving-permissions-and-rbac-in-cloned-databases-mo9)
- [Part 4: Clone++ Parallelization and Production Features](https://dev.to/swaroop_krishna_e2f4b83b2/part-4-parallelization-and-production-features-3b3d)

### Salesforce & Snowflake Integration
- [Salesforce to Snowflake, With Less Friction: Zero-Copy V2 in Practice](https://dev.to/swaroop_krishna_e2f4b83b2/salesforce-to-snowflake-with-less-friction-zero-copy-v2-in-practice-4435)
- [Part 1: Zero-Copy Sharing – Salesforce Snowflake for Analytics](https://dev.to/swaroop_krishna_e2f4b83b2/part-1-zero-copy-sharing-salesforce-snowflake-for-analytics-4f0j)
- [Part 2: Zero-Copy Data Federation - Snowflake Customer 360 Data to Salesforce Sales Reps](https://dev.to/swaroop_krishna_e2f4b83b2/part-2-reverse-zero-copy-activating-customer-360-in-salesforce-3c2b)

### AI & Snowflake Agents
- [My Snowflake Agent Was Wrong. So Was My Evaluation.](https://dev.to/swaroop_krishna_e2f4b83b2/my-snowflake-agent-was-wrong-so-was-my-evaluation-1b46)
- [Natural Language Is the Interface, Not the Semantic Layer](https://dev.to/swaroop_krishna_e2f4b83b2/natural-language-is-the-interface-not-the-semantic-layer-ce9)
- [From Optimization to Protection: Adding a Security and Governance Agent to Your Snowflake Multi-Agent Team (Part 3)](https://dev.to/swaroop_krishna_e2f4b83b2/from-optimization-to-protection-adding-a-security-and-governance-agent-to-your-snowflake-369f)
- [Ask Your Snowflake Account Anything — Build an AI Admin Agent with Cortex + GitHub Copilot (Part 1)](https://dev.to/swaroop_krishna_e2f4b83b2/ask-your-snowflake-account-anything-build-an-ai-admin-agent-with-cortex-github-copilot-1mk6)
- [From One Agent to Many: Building a Multi-Agent Team for Snowflake Administration (Part 2)](https://dev.to/swaroop_krishna_e2f4b83b2/from-one-agent-to-many-building-a-multi-agent-team-for-snowflake-administration-part-2-379d)

### Microsoft Fabric & Power BI
- [When Zero-Copy and Mirroring Clash: An Iceberg Metadata Gotcha — Part 3](https://dev.to/swaroop_krishna_e2f4b83b2/when-zero-copy-and-mirroring-clash-an-iceberg-metadata-gotcha-part-3-de3)
- [Mirroring Snowflake Iceberg into Microsoft Fabric: The Gotchas — Part 2](https://dev.to/swaroop_krishna_e2f4b83b2/snowflake-iceberg-fabric-what-we-tried-what-support-confirmed-and-what-comes-next-ie0)
- [Setting up Snowflake–Power BI Connectivity with Azure AD SSO and Auto-Provisioning](https://dev.to/swaroop_krishna_e2f4b83b2/setting-up-snowflake-power-bi-connectivity-with-azure-ad-sso-and-auto-provisioning-1gda)

### Preserving Business Meaning During Modernization
- [Leaving SAP HANA? Understand What You’re Taking With You.](https://dev.to/swaroop_krishna_e2f4b83b2/leaving-sap-hana-understand-what-youre-taking-with-you-5h70)
- [Moving Data Is Easier Than Moving Knowledge](https://dev.to/swaroop_krishna_e2f4b83b2/moving-data-is-easier-than-moving-knowledge-2co4)

### SAP HANA Technical Content (SAP Community / SCN)

#### SAP HANA Modelling & SQL Scripting
- [SAP HANA: Using "Dynamic Join" in Calculation View (Graphical)](https://blogs.sap.com/?p=99974)
- [SAP HANA: Handling Dynamic Select Column List and Multiple values in input parameter](https://blogs.sap.com/?p=99089)
- [Using Multiple Values in Input parameter for filtering in Graphical Calculation View](https://blogs.sap.com/?p=99677)
- [SAP HANA: Workaround for using Commit & Rollback in exception handling block of a Stored Procedure](https://blogs.sap.com/?p=99553)
- [SAP HANA: Replicating Data into SAP HANA using HDBSQL](https://blogs.sap.com/?p=98876)

#### Predictive Analytics & Machine Learning on HANA
- [SAP HANA: My experiences on using Predictive Analysis Toolset with HANA (PAL)](https://blogs.sap.com/?p=64845)
- [SAP HANA: My Experiences with SAP Business Objects Predictive Analysis tool](https://community.sap.com/t5/user/viewprofilepage/user-id/182302)

</details>

## Community contributions and recognition

### Sharing knowledge and supporting others

- **Writing and education:** I publish practical technical articles and Data Platform Field Notes to make implementation lessons, tradeoffs and failure modes useful to other engineers.
- **Community answers:** My [SAP Community archive](https://community.sap.com/t5/user/viewprofilepage/user-id/182302) records contributions dating back to 2010. Its totals include discussions and answers, not just articles; the migrated profile is displayed as `former_member182302`.
- **Speaking and event organization:** Organizer and speaker at SAP Inside Track Chennai 2014; awarded **Top Speaker (1st Prize)** at both Chennai (July 2014) and Hyderabad (September 2014). [Chennai event account](https://community.sap.com/t5/technology-blog-posts-by-members/sap-inside-track-chennai-2014-from-an-scn-fan-perspective/ba-p/13107742).
- **Nvolve mentoring:** Contributed as a volunteer mentor with Nvolve, supporting its work to help women pursue STEM careers.
- **Technical mentoring:** Knowledge-sharing sessions and guidance for data engineers and SAP HANA practitioners, alongside mentoring within engineering teams.

### Community recognition

- **Snowflake Squad — 2026:** [Official Snowflake badge](https://developerbadges.snowflake.com/5c0df258-d1b8-4814-af86-1cce7d7e2bdc), issued September 3, 2026.
- **SAP HANA Distinguished Engineer — March 2014:** [SAP Community announcement](https://community.sap.com/t5/technology-blog-posts-by-members/krishna-tangudu-hana-distinguished-engineer-and-poet/ba-p/13073641).
- **SCN Topic Leader — SAP HANA, twice:** [2011–2012 announcement](https://community.sap.com/t5/welcome-corner-blog-posts/announcing-the-scn-topic-leaders-2011-2012/ba-p/12942399) and [2013–2014 announcement](https://community.sap.com/t5/welcome-corner-blog-posts/recognizing-the-scn-topic-leaders-for-2013-2014/ba-p/13099614). Listed under SAP HANA and In-Memory Computing as `krishna.tangudu2` and `krishna.tangudu`, respectively.
- **SCN Active Contributor GOLD — May 2012:** Recognition for contributions to SAP Community Network.

## Professional background

I am a **Data Architect at Agilent Technologies**, based in the San Francisco Bay Area, with earlier SAP BI and HANA roles at Infosys and Tech Mahindra. My experience connects enterprise implementation with community education: cloud data architecture, SAP modernization, Snowflake governance and optimization, Iceberg interoperability, and AI-assisted data discovery.

**Education:** Master's in Business Analytics, California State University, East Bay.  
**Certifications:** SnowPro Core; four SAP certifications covering HANA 1.0, BO 4.0, BODS 3.x and BI 7.0.

<details>
<summary>Employer awards and delivery recognition</summary>

| Date | Honor or award | Issuer | Contribution recognized |
| --- | --- | --- | --- |
| Aug 2019 | **GIS One Agilent Award** | Agilent Technologies | Individual Contribution at Enterprise Analytics Team |
| Mar 2019 | **ACG Unit Award — SSD/LED headquarters and ADS** | Agilent | Crosslab Service Analytics |
| Mar 2019 | **ACG Group Award — Sales SAPKJ** | Agilent | Distributor Order Reporting Process Simplification |
| Mar 2019 | **GIO Special Unit Award — Global Operations Team** | Agilent | AcoE High Performance Analytics |
| Aug 2015 | **INSTA Award** | Infosys | Contributions and dedication to UOV deliverables, plus HANA technical support for other accounts and proposals |
| Apr 2015 | **Tech Champion** | Infosys | Project execution and SAP HANA articles during Q3FY15 |
| Jan 2015 | **Key Contributor** | Infosys | Project execution and SAP HANA articles during Q2FY15 |
| May 2012 | **Pat On the Back (POB)** | Mahindra Satyam | Work for Nestlé |
| Apr 2012 | **Associate of the Month** | Mahindra Satyam | SCN community contributions and representing the Mahindra Satyam SAP BI practice |

</details>

## Connect and collaborate

I'm interested in sharing implementation experiences, contributing technical walkthroughs, speaking about data-platform lessons and helping others build reliable systems on Snowflake.

[Connect on LinkedIn](https://www.linkedin.com/in/krishna-tangudu-1a961319/) · [Read the newsletter](https://www.linkedin.com/newsletters/data-platform-field-notes-7465407764811452416/) · [Explore my repositories](https://github.com/LALITHASWAROOPK)

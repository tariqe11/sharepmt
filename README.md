Thank you for your interest in the Assistant Manager - Data Analyst role with us. I enjoyed reviewing your profile.

Before we set up a conversation, I'd like to cover a few basics to ensure the role is the right fit for you and make the best use of our discussion. Could you please share the following details?

1. Are you actively considering a job change at this time? If yes, what is prompting the move?

2. What interests you most about this role?

3. Current CTC (Fixed + Variable)

4. Expected CTC / Compensation Range

5. Notice Period (including whether it is negotiable or if a buyout option is available)

6. Current Location

7. Willingness to relocate to Gurgaon

8. Can you walk me through a project where you automated a manual reporting or data processing task using Python, SQL, VBA, or Power BI? What was the challenge, your approach, and the business impact?

9. Explain how you would analyse the performance of an investment portfolio. What metrics would you review, and how would you identify the key drivers of performance and risk?

10. Please share your resume.

Once I receive these details, I'll update you on the next steps. If there appears to be a strong alignment, I'll arrange a call to discuss the role and team in greater detail.

Looking forward to hearing from you.

Thanks & Regards

Mehak Chawla | Assistant Manager - Talent Acquisition| Fidelity International

FIL India Business and Research Services Private Limited

Building No. 9, Candor Tech Space, Sector 48, Gurgaon - 122018, Haryana, India

M: +91 7428580896 | http://www.fidelityrecruitment.com

Connect : LinkedIn | Twitter | Facebook     Review : Glassdoor

 

The information transmitted is intended for the person or entity to which it is addressed and may contain confidential, privileged or copyrighted material or attorney work product. If you receive this in error, please contact the sender and delete the material from any system. Any unauthorised copying, disclosure or distribution of the material in this e-mail is strictly forbidden. Any comments or statements made are not necessarily those of Fidelity. All e-mails may be monitored or recorded.
Hi Mehak,
 
Thanks for the offer, I looked up the JD and Hiring Manager profiles, interested to know more about the job role, with that said answering your questions (I tried to write as precise as possibe but fet the project needed itte more expanation).

1. I'm just active in the market to learn more about new job roles and responsibilities, new challenges faced in the data world and ensuring that I'm staying up to date with the market.

2. Few things which really sparked my interest about this role:
The team spans Systematics, Fixed Income, Equities and Multi Asset. 
Proximity to the client: Today I work on a product-based project where priorities reach me through Product and Sales reports, This role puts me alongside Investment Directors, Specialists and Portfolio Managers, and closer to the client requirement itself. I'd rather hear the problem first-hand, scope it properly, and build the right thing.
The reporting line. I read up on a few Associate Directors profiles in linkedin their achievements, years of experience in these fields and their active engagement in other areas along with Pairing his depth on the investment side with what I bring on data and automation is a genuinely strong learning structure for me.
3. CTC Current:
9 LPA All filxed
4. Expected CTC:
I'm happy with the current market range for this role, and I'm more interested in knowing about the current project I'll be working, what is expected from me in the 6 months, what problems the business is facing/trying to solve currently.  
5. Notice Period:
60 Days (Negotiable, can buyout 30 days)
6. Current Location: Bengaluru

7. Relocating: Yes, I'm okay with relocating to Gurugram.
 
8. Projects: Automating a manual reporting / data processing task

Overview: Rebuilt UK corporate filings workflow from a fully manual process (roughly 50 min) per analyst touch time per company, six-month data lag into an automated pipeline with a 24-hour detection window.

i) Python: Automated data pull from the UK registry (API)

Challenge

-        Analysts manually checked every company in our database for new filings; most had none, so the majority of effort produced no output.

-        Checks ran on a cycle; a company filing just after a check wouldn't be picked up for another six months.

-        Stale data drove recurring client tickets.

Approach

-        Connected to the Companies House API via Python and ran it against our full company list.

-        Moved from a monthly manual query to a scheduled daily run connected directly to the database.

Business impact

-        New filings surfaced within 24 hours of appearing in the registry.

-        Analyst time redirected to companies that actually had updates

-        processing volume up 70%.

-        Freed capacity for ad-hoc requests and new initiatives.

-        Client tickets on new filings are down 50%






ii) Python: Data Extraction using python scripts

Challenge

-        Manual copy-paste from filing PDFs into Excel — averaging 10 minutes per filing.

-        Filings with 200+ shareholders were effectively unprocessable manuals.

-        Power Query extraction produced inconsistent output.

Approach

-        Built a Python extraction pipeline (used PyPDF2, Tesseract and PaddleOCR packages).

-        Added routing logic to handle native-text, scanned/non-OCR and handwritten filings.

-        Output delivered as a clean Excel file, ready for downstream processing.

Business impact

-        Extraction time of 10 minutes is completely cut — a 100% reduction in processing time.

-        Removed the shareholder-count ceiling entirely, able to process even 2000 investors rows.

-        UK dataset coverage increased by 35%, including filings we previously couldn't capture at all.




iii) Python: File conversion utility

Challenge

-        Analysts raised individual Adobe Acrobat licences for short-term conversion needs;

-        licences lapsed after 90 days of inactivity, forcing repeat requests.

-        Online conversion tools were blocked for security and data-compliance reasons.

Approach

-        Built a Python converter that auto-detects the input file type and delivers the user's chosen output format.

-        Covers all major filing types, including multi-page TIFF.


Business impact

-        Adopted as the team standard for file conversion. Licensing spend reduced by 85%,

-        Removed a recurring administrative request cycle.




iv) VBA: Cap table preparation (dynamic data processing) 

Challenge

-        An average of 10–15 minutes per company spent on data cleaning and cap table construction.

-        No standard method across the team, causing inconsistency and timeliness issues.

Approach

-        Built VBA scripts to clean the extract and construct the cap table automatically.

-        Generates the pivot, segregates individual vs. institutional investors, runs the calculations, and auto-recalculates when an analyst makes a manual edit.

Business impact

-        Cleaning time is cut from 10–15 minutes to 5 minutes.

-        Manual calculation errors effectively eliminated.

-        Uniform output structure across all analysts — the control improvement that made the next stage possible.


v) End-to-end automation (Detection → extraction → cleaning → direct upload)
Challenge


-    Even with structured data, analysts re-keyed it into the front end spending 10 minutes per captable of clicking and pasting.


Approach

-    Chained the components into a single flow: API detection → trigger → Jira ticket → automated extraction to Excel → VBA cleaning and segregation → direct upload to front end. (Prototype built with Power Apps, Power Automate and Lists; currently in development with the Engineering team.)


Business impact

-        Targets full elimination of the ~10-minute manual upload per captabe.

-        Analyst role shifts from doing the work to reviewing the output.

-        End-to-end: 85% of manual touch time removed across the workflow (across a jurisdiction dataset).


vi) Other projects

AI / Copilot initiatives

Agent orchestration for Web Research:

-        Multi-agent setup that researches data the way an analyst would

-        with tasks assigned across agents (currently in test with selected analysts).

AI optimisation:

-        identified friction in how the division used AI for data cleaning and built a scalable solution (Python script + vision model + LLM routing) that selects the right resource per use case.

-        Reducing run time, improving output reliability, and handling complex cases on lighter models. (Pending rollout).

Jira KPI reporting

-        Automated a weekly KPI report to each analyst,

-        enabling individuals to plan and track their own delivery rather than discovering gaps at period end.

Jurisdictional coverage

-        Valuations and cap table processes across the UK, Ireland, Poland, Spain and Germany covering the EMEA region and all deal types. 

Added my SQI and other projects in the resume



9)  Analysing performance of an investment portfolio:

Answering on a high eve I'd start by fixing the reference points, benchmark, period, currency and whether we're looking at gross/net returns, because everything after that depends on them. Then I'd look at absolute and excess return, on rolling periods rather than a single snapshot, to see whether performance is consistent or down to one or two episodes.


Looking forward to know more about the Role.
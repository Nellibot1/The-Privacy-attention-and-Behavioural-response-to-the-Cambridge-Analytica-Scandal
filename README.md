
# Privacy attention and Behavioural response to the Cambridge Analytica Scandal (Issue attention cycles and privacy related search dynamics)

## Background
Major scandals can trigger sudden public concern, the issue-attention cycle predicts declining public concern after initial interest. But less is known about the duration and nature of attention, especially in the context of privacyrelated scandals. Online search behavior provides a real-time proxy for public interest and behavioral intent. The Cambridge Analytica scandal was a pivotal event that raised public awareness of data privacy causing different attitudes towards privacy rights.

## Research Question
How did public privacy concern evolve after the Cambridge Analytica scandal?

**Analysis Methodology**
* **Privacy Concern Index = mean of relevant** Overlay the event timeline on the search volume charts.
* **Event date: 17 March 2018** Measure how many days it takes for search volume to return to baseline after a peak.
* **Wilcoxon signed-rank test:** ⟶ Nullhypothesis: Difference between
the medians equals zero
⟶ Alternative Hypothesis: Interest 6 months
after the scandal is still higher than before
inital rise
Recovery = return to pre-event baseline (14-day
mean)

## Group Members

Janniella Heimig
Felix Kaltenegger
Antonia Windisch

=======
<<<<<<< HEAD
# Privacy attention and Behavioural response to the Cambridge Analytica Scandal (Issue attention cycles and privacy related search dynamics)

##Background
Major scandals can trigger sudden public
concern, the issue-attention cycle predicts
declining public concern after initial interest.
But less is known about the duration and nature
of attention, especially in the context of privacyrelated
scandals.
Online search behavior provides a real-time
proxy for public interest and behavioral intent.
The Cambridge Analytica scandal was a pivotal
event that raised public awareness of data
privacy causing different attitudes towards
privacy rights.

##Research Question :
How did public privacy concern evolve after the
Cambridge Analytica scandal?
>>>>>>> bc439ff0097fa2ab553eb6b3cc1471d47efe7a8b

## Project Phases

**1. Data Collection & Preparation**

- **Source:** Google Trends (via Python/pytrends). Optionally: Reddit
- **Timeframe:** 2018–2024.
- **Target Region:** Worldwide.
- **Keywords:**
    * *Action-oriented:* "delete Facebook", "VPN", "GDPR", "encrypt".
    * *Product-oriented (Download Proxy):* "Signal", "Threema", "Telegram", "DuckDuckGo".
    * *Control Group:* "WhatsApp Web", "Instagram login".

> The category of keywords is preliminary. It may change according to our research.

**2. Event Categorization (The Independent Variables)**

There are in particular two situations that raises privacy concerns within the society:


* **Security Incidents:** Data breaches, leaks, scandals (e.g., Cambridge Analytica, Pegasus, Facebook leaks).

> This is preliminary. There are possibly more, but we need a paper or two to substantiate this point.

**Task:** Create a precise timeline table containing the event date, first media coverage date, and perceived severity level.



---

## Timeline, Deliverables and Deadlines

Per Deliverable, we define two deadlines: a **Check-In** for reporting on the progress, and a **Hand-In**, where the deliverable is on the GitLab, if applicable.

0. Project Inception
    - Setting up the GitLab repository
    - Define the project scope
    - **Deadline**: 30.11.2025, 17:00
    - *Deadline 2* (if changes are necessary): 02.12.2025, 13:00
1. Data Retrieval
    - Finding a security incident and keywords (5 in total each one)
    - Finding Data (Google Trends) and uploading them to GitLab
    - Find literature about works that have analyzed Google Trends as well and what they have done so far (What keywords, when an increase of interest is considered significant, ...)
    - **Check-In**: 02.12.2025, 13:00 (or later, depending on the Project Inception)
    - **Deadline**: 07.12.2025, 23:59
2. Implementation
    - Performing analysis depending on the keywords and the security incidents
    - Finding correlations
    - Peak-to-Baseline Ratio & Decay rate
    - Performing a visual analysis
    - ...
    - **Check-In 1**: 09.12.2025, 13:00
    - **Check-In 2**: 16.12.2025, 13:00
    - **Deadline**: 03.01.2026, 23:59
3. Christmas Break buffer
4. Poster Design
    - **Check-In**: 06.01.2026, 13:00
    - **Deadline**: 11.01.2026, 23:59
6. **POSTER PRESENTATION**: 27.01.2026



Whoever misses a deadline (Check-In or Deadline) thrice and without notice, will be reported to the Lecturers team.





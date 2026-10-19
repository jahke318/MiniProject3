# MiniProject3 Disagreement Examples

## Example 1 - FreeSurfer HasRecovered

**Project ID:** freesurfer_freesurfer  
**Project Owner:** jmill291  
**Validator:** bdowlin2  
**Field:** HasRecovered  

**Author Value:** N/A active Project  
**Validator Value:** No  

**Discussion and Evidence:**  
The supplied FreeSurfer timeline did not contain any zero-commit months. Brett used "No" because no recovery event occurred, while my original value used N/A because the project never became inactive. We determined that both values were trying to express the same underlying situation.

**Adjudicated Value:** N/A: no observed inactivity gap  
**Resolution Type:** Compromise  

We agreed that N/A is clearer because there was no inactivity period from which the project needed to recover.


## Example 2 - Falcor Currentstatus

**Project ID:** nvidiagameworks_falcor  
**Project Owner:** jmill291  
**Validator:** bdowlin2  
**Field:** Currentstatus  

**Author Value:** Active  
**Validator Value:** Inactive  

**Discussion and Evidence:**  
My original classification relied on the supplied WoC history, which contained commits during 2025. Brett checked the upstream default GitHub branch and found that the latest eligible commit before the September 30, 2025 cutoff was January 7, 2025. The coding rule defines the active window as April 1, 2025 through September 30, 2025.

**Adjudicated Value:** Inactive  
**Resolution Type:** ValidatorKept  

We agreed to use the default-branch GitHub cutoff consistently, making the project Inactive.


## Example 3 - NeuroElectro RecentThemes

**Project ID:** neuroelectro_neuroelectro_org  
**Project Owner:** jmill291  
**Validator:** bdowlin2  
**Field:** RecentThemes  

**Author Value:** Documentation updates:Automated bot contributions  
**Validator Value:** Documentation updates:Feature development  

**Discussion and Evidence:**  
Brett reviewed the latest ten default-branch commits and found three documentation updates, three feature-development commits, two bug fixes, and two Other commits. There were no bot-authored commits in those ten entries. My automated-bot classification came from a different WoC data scope rather than the ten default-branch commits used for this field.

**Adjudicated Value:** Documentation updates:Feature development  
**Resolution Type:** ValidatorKept  

We agreed that Documentation updates and Feature development better represent the actual latest-ten-commit sample.

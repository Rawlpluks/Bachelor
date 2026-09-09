The specified terms and conditions proposed by [[Key people|Katrine Frederikesen]] at [[ERGO]].
These must be complied with, otherwise [[ERGO]] has retained the right to cut off the data supply.

The agreed upon terms are as follows:
- The project goes ahead as a *strictly controlled internal [[ERGO]] analysis*, not an external research project. 
- Clara will be working in her capacity as a student actuary eomployee, under the department's instruction.

- Data stays inside [[ERGO]]'s environment, not raw-data export.
- Only aggregated, reviewed output leaves - model performance, computation times, descriptive stats, nothing person-identifiable or financial in absolute terms
- Dataset is heacily reduced, especially on timestamps and granularity 
- Access is limited to a clearly defined setup.

- The project will produce three internal deliverables (relayed by [[Key people|Frederikke Horn]]) act as the accepted justification for [[ERGO]]'s own benefit:
	1. An internal ML-vs-chain-ladder benchmark on a real [[ERGO]] portfolio - notably a *[[long-tail]]* line, where the original paper only tested [[short-tail]]
	2. Insight into what drives notification-delay heterogeneity, relevant for IBNR, claims-handling capacity, and Solvency II technical provisions
	3. Reproducible code and in-house experience with the method

- Accepted minimum data spec:
	- Fresh anonymous [[claim ID]]
	- [[Accident time]] reduced to month/quarter
	- [[Reporting date]] reduced in granularity
	- [[Snapshot date]]
	- Health information stays at coarse category level only ([[Product type]], [[Cause of loss]])
		- No individual-level sensitive detail

Additional [[Key people|Katrine Frederikesen]] requires final confirmation/concretisation of:
- **[[Anonymisation]]** - how the variable combination is handled so indirect-identification risk is genuinely eliminiated
- **[[Output control]]** - who does the final review/approval before anything is used outside [[ERGO]]
- **Purpose and use** - explicit confirmation the analysis is internal, and that the thesis only uses approved, aggregated, non-identifiable results
- **Access and roles** - confirm access is fully restricted and the work is done solely in the student-employee role under [[ERGO]]'s instruction.
# Week 4 retrospective

1. What changed between your Part A checkpoint and final Part B result?

In Part A, I mainly reviewed the supplied data, metadata, CRS information, feature counts, and geometry validity. In Part B, I completed the spatial join, compared the within and intersect predicates, created a map layout, and added a text-table equivalent. The final result showed that all 5 facilities matched service zones.

2. Which reviewer observation did you accept, reject, or defer? Why?

A peer review request was sent to a classmate, but the completed review had not been returned before the submission deadline. Therefore, no reviewer observation was available to accept or reject, so this item was deferred.

3. Which parameter or assumption most changed the result?

The spatial predicate was the main parameter tested. I compared within with intersect. Both produced a count of 5 matched facilities, so changing this parameter did not change the result or recommendation.

4. What could still make the output look plausible while being wrong?

The output could still look correct even if the CRS were assigned incorrectly, if the source data contained unnoticed errors, or if the fictional service-zone boundaries did not represent real operational conditions.

5. What evidence is still missing before operational use?

Before real-world use, current authoritative data, verified CRS information, real source provenance, confirmed licences, updated dates, and evidence that the service zones accurately represent real conditions would be required.

6. How did you consider accessibility, location privacy, community impact, and Indigenous data authority?

The map includes a title, legend, scale information, CRS information, and a text-table equivalent so the main finding can be understood without relying only on colour. The supplied data are fictional, so no real personal or sensitive locations were used. Real-world use would require consideration of community impact, location privacy, and appropriate Indigenous data authority where applicable.

7. What AI assistance, if any, was used? How did you verify it?

AI assistance was used to help interpret the lab instructions, organize the workflow, and draft explanations for the required files. The work was verified by checking the supplied metadata, source inventory, QGIS attribute tables, geometry-validity results, spatial-join logs, and saved outputs before submission.
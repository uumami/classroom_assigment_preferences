# classroom_assigment_preferences
Match Making Algorithm for solving the Classroom Assignment Problem by Aggregating Preferences

This paper proposes a novel approach to solve the \textit{classroom assignment problem}, which is a well known NP-Hard multi-objective optimization problem, as a \textit{match-making problem}. In order to generate the preferences we ask the professors and students asses their own preferences over possible set of classrooms. Furthermore, we propose a democratic mechanism to aggregate students' preferences. This democratic approach present flexible characteristics that can be adapted by the planner. The mechanism can follow the standard democratic approach and aggregate votes or impose any type of voting system like Borda count. We show that any mechanism that aggregates preferences or represents preferences can help model the problem as a match-making one as long as it satisfies some assumptions. Mainly if preferences can be represented as a matrix the problem can be solved with a match-making algorithm. We proceed to analyze the complexity of the algorithm and the normative implications of our approach. Finally, we propose a tie-breaker method that helps minimize the overlap of the courses for the alumnae. The complexity of our algorithm is $O(n^4)$.

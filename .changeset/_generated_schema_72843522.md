---
"@linear/sdk": minor
---


feat(schema): [dangerous] Input field 'usePrioritySortOrderTiebreaker' was added to input object type 'PrioritySort' (PrioritySort.usePrioritySortOrderTiebreaker)

feat(schema): [dangerous] Argument 'filter: ReleaseNoteFilter' added to field 'Query.releaseNotes' (Query.releaseNotes.filter)

feat(schema): [dangerous] Input field 'type' was added to input object type 'ReleasePipelineCollectionFilter' (ReleasePipelineCollectionFilter.type)

feat(schema): [dangerous] Input field 'type' was added to input object type 'ReleasePipelineFilter' (ReleasePipelineFilter.type)

feat(schema): [non_breaking] Type 'InitiativeVisibility' was added (InitiativeVisibility)

feat(schema): [non_breaking] Type 'ReleaseNoteFilter' was added (ReleaseNoteFilter)

feat(schema): [non_breaking] Type 'ReleasePipelineTypeComparator' was added (ReleasePipelineTypeComparator)

feat(schema): [non_breaking] Field 'visibility' was added to object type 'Initiative' (Initiative.visibility)

feat(schema): [non_breaking] Field 'InitiativeLeadTeamChangeImpact.affectedDescendantCount' description changed from 'The number of editable sub-initiatives whose lead team would change if the update is applied to descendants.' to 'The number of editable matching sub-initiatives whose lead team would change if the update is applied to descendants. Matching sub-initiatives currently have the same lead team as the selected initiative had before the change.' (InitiativeLeadTeamChangeImpact.affectedDescendantCount)

feat(schema): [non_breaking] Field 'leadTeamId' was added to object type 'InitiativeWebhookPayload' (InitiativeWebhookPayload.leadTeamId)

feat(schema): [non_breaking] Field 'Mutation.initiativeLeadTeamUpdate' description changed from '[Internal] Updates an initiative's lead team, optionally applying it to affected editable sub-initiatives.' to '[Internal] Updates an initiative's lead team, optionally applying it to matching editable sub-initiatives.' (Mutation.initiativeLeadTeamUpdate)

feat(schema): [non_breaking] Description for argument 'mode' on field 'Mutation.initiativeLeadTeamUpdate' changed from 'Whether to update only the selected initiative or also affected editable sub-initiatives.' to 'Whether to update only the selected initiative or also matching editable sub-initiatives. Matching sub-initiatives currently have the same lead team as the selected initiative had before the change.' (Mutation.initiativeLeadTeamUpdate.mode)

feat(schema): [non_breaking] Field 'Query.initiativeLeadTeamChangeImpact' description changed from '[Internal] Returns the impact of changing an initiative's lead team before applying the update.' to '[Internal] Returns the impact of changing an initiative's lead team before applying the update to matching sub-initiatives.' (Query.initiativeLeadTeamChangeImpact)

feat(schema): [non_breaking] Field 'url' was added to object type 'ReleaseNote' (ReleaseNote.url)

feat(schema): [non_breaking] Field 'showTeamInitiatives' was added to object type 'ViewPreferencesValues' (ViewPreferencesValues.showTeamInitiatives)

feat(schema): [non_breaking] Field 'teamInitiativesShowContributing' was added to object type 'ViewPreferencesValues' (ViewPreferencesValues.teamInitiativesShowContributing)
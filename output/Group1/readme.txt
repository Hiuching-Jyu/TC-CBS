this group is tested under the following situation
1. the code updated Jun 28 2023 in GitHub
2. the code "for (size_t timestep_i = 0; timestep_i <= min_timestep; timestep_i++)"in function "vector<pair<size_t,size_t>> CBS::findDuplicateConflicts(CBSNode& curr, bool do_duplicate)" used max_timestep instead of min_timestep in the group.

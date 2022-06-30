---
name: Genome assembly update
about: Tasks necessary to update i5k Workspace resources after a genome assembly update.
title: 'Genome assembly update: [Genus species]'
labels: content
assignees: ''

---

# OGS remapping

- [ ] request whole-genome alignment
- [ ] Set up data directories and get data
- [ ] run remap-gff3

# Change old content
- [ ] back up and deprecate old Apollo2
- [ ] back up and deprecate old fasta files in BLAST 
- [ ] back up and deprecate old fasta files in Hmmer 

# Add new content to i5k Workspace applications
See https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update for full description of each task (requires gitlab login)

- assembly accession number:
- publication associated with assembly:
- due date:
- community contact:

## Tasks on Ceres:
- [ ] 1. Run the final_workflow.cwl component of the organism_onboarding pipeline (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#1-run-the-final_workflowcwl-component-of-the-organism_onboarding-pipeline-httpsgithubcomnal-i5korganism_onboarding)
- [ ] 2. Run RNA-Seq pipeline, steps 1 and 2 (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-RNA-Seq-data-to-an-i5k-Workspace-project-with-the-NAL_RNA_seq_annotation_pipeline)

## Tasks on the NAL servers:  
- [ ] 1. Move the final_workflow.cwl output from SCINet to apollo2-stage-node1 (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#3-move-the-final_workflowcwl-output-from-scinet-to-apollo2-stage-node1)
- [ ] 2. Apollo setup on the apollo2-stage-node1 and apollo2-node1 servers (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#4-apollo-setup-on-the-apollo2-stage-node1-and-apollo2-node1-servers) 
- [ ] 3. Set up Tripal pages (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#6-set-up-tripal-pages)
- [ ] 4. Set up BLAST and HMMER (genomics-workspace) (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#7-set-up-blast-and-hmmer-genomics-workspace)
- [ ] 5. Set up data downloads (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#8-set-up-data-downloads)
- [ ] 6. Functional annotation (@amcooksey)
- [ ] 7. Final Test List (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#10-final-test-list)
- [ ] 8. Advertising (https://gitlab.com/i5k_Workspace/workspace_roadmap/-/wikis/Adding-an-organism-CWL-update#10-advertising) (@mpoelchau)

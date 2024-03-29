## Examples created for SIMA 4.4


  

| Case | Description    |Tags|
|:---|:---|:---|
| [Differentiation using JavaScript and workflow operator](differentiate_using_javascript.stask)| This example show how you can use JavaScript or the workflow operator _differentiation_ . <br />The JavaScript's can be used as basis for creating other functions. |`JavaScript`|
| [An editor to read and plot the content of an mpf-file](mpf_plotter.stask)| Running Riflex standalone an ascii-file of type mpf is created. <br /> This is an example on how you can read the file in SIMA.|`Standalone` `Riflex` `ascii` `mpf`|
| [Decay analysis](decay_examples.stask)| This example show how to do a decay analysis using static displacement and specified force | `decay` `specified force` `displacement`|
| [OpenFAST model of the IEA 15 MW WT](IEA15MW_turbine_only_draft_version_20221007.stask) | **_NOTE:_** <br /> This is a draft version of the IEA 15 MW WT (based on the OpenFAST model). The implementation of a verified model is work in progress. <br />The model includes the turbine only. <br />The model is _NOT_ verified. <br /> <br />  Before running the model:<br /> Open the file **DISCON_< >.IN**. Set the correct path to the file containing rotor performance tables (Cp,Ct,Cq). The name of the file is **Cp_Ct_Cq.IEA15MW.txt** |`wind` `IEA15MW`|
| [OpenFAST model of the IEA 15 MW WT - ROSCO v2.6.0](IEA15MW_ROSCO2.6.0_turbine_only_draft_version_20221021.stask) | **_NOTE:_** <br /> This is a draft version of the IEA 15 MW WT (based on the OpenFAST model). The implementation of a verified model is work in progress. <br />The model includes the turbine only. <br />The model is _NOT_ verified. <br /> <br />  Version 2.6.0 of the ROSCO controller is used. A direct path for the performance file is _not_ required in this new version.|`wind` `IEA15MW` `Rosco`|
| [Running analysis and post-processing ](RunAndPostProcSeparate_copyFilescopyResults.stask)| Running analysis and post-processing in two steps using workflow sets. Simple custom editor is included. <br/> Files are copied to folders, see workflows `run_singlecase` and `wf_copy_files` <br/> **_NOTE_:** <br/> The files are made available by making a list of files in the _condition run -> File output_, see  `run_singlecase`   |`Custom editior`,`post-process`,`copy files`|
| [Run model and calculate fatigue damage](example_fatigue_using_workflowset_and_postproc.stask)| Run a model for  a set of sea states defined in an input file, see storage task `ST_fatigue/input/`. The fatigue damage is calculated for selected location along the riser, see worfklow `FLS.run_loop -> FLS.wf_calcFatigue` |`fatigue` 

<!---#That is so funny! :joy: :tent:-->

<!---
- [Comparison Marine growth conditionset](comparison_marine_growth_conditionset_in_wf_set_with_CE_report.stask)
  - Model marine marine growth. 
    - Example includes a custom editor and a report generator.
- [How to use error log in a workflow set](Error_log_example_with_two_sets.stask)
  - Log of the failed cases a stored to file
- [Condition and workflow as input](Example_condition_and_workflow_as_input_report.stask)
- [Post processor operators](examplePostProcessorOperators.stask)
  - This is included in SIMA 4.2.0
- [Pass signal to an Excel file](Example_send_signals_to_Excel_sheets.stask)
- [Store data to file](storeDataToFiles.stask)

-->
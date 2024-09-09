## Examples created for SIMA 4.6
  
###  SIMA 4.6.0

| Case | Description    |Tags|
|:---|:---|:---|
| [User defined element](CatenaryRiser_userdefined_element.stask)| This example shows to user a user-defined element to create a flat bottom. Fortran code for the user-defined element may be found in `template_code/earth_example.f90` and the compiled code in `earth_example.dll`. <br /> <br /> **NOTE**:  The interface code in Fortran 90 included in the storage task `template_code/earth_interface.f90` |`User defined element`|

### SIMA 4.6.3

| Case | Description    |Tags|
|:---|:---|:---|
| [TTR, Time domain VIV (Cross flow load)](sima463_example_ttr500m.stask)| This example shows how to include the effect of VIV due to current and waves in a time domain simulation. <br />A simple TTR model is included together with workflows and a small custom editor to run the analysis and view results.<br /> <br /> *Only cross-flow VIV loads are applied as the in-line loads are still restricted to the JIP participants.* |`Time domain VIV, Cross-flow loads` <br /> `Wave & Current` <br /> `TTR (top tensioned riser)`|
| [Calculate relative distance between points](sima463_Calculate_relative_distance_between_points.stask)|This example shows how to use a workflow to calculate the relative distance between two points. This approach can be extended to find the relative distance between two bodies. | `workflow`, `transform point`, `relative position`,`bodies` 


### SIMA 4.6.4

| Case | Description    |Tags|
|:---|:---|:---|
| [FOWT, Time domain VIV (Cross flow load)](ima464_Spar_OWT_DNV.stask.stask)| This example shows how to include the effect of VIV due to wave & current in a time domain simulation. <br/>A FOWT is modelled including workflows and a small custom editor to run the analysis and view results. <br/><br/>**NOTE**: _The purpose of this model is to illustrate the effect of VIV loads_. A check has been performed to ensure that the hydrodynamic coefficients are reasonable. <br /> <br />This example was collaboratively created with the assistance of [DNV](https://www.dnv.com/services/marine-operations-and-mooring-analysis-software-sima-2324) <br /> <br /> *Only cross-flow VIV loads are applied as the in-line loads are still restricted to the JIP participants.*|`Time domain VIV, Cross-flow loads` <br/> `Wave, Current, Wind` <br/> `FOWT, NREL5MW`, `DNV`|

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
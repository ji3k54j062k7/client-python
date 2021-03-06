# K8sIoApiCoreV1PersistentVolumeClaimStatus

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_modes** | **list[str]** | AccessModes contains the actual access modes the volume backing the PVC has. More info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#access-modes-1 | [optional] 
**capacity** | [**dict(str, K8sIoApimachineryPkgApiResourceQuantity)**](K8sIoApimachineryPkgApiResourceQuantity.md) | Represents the actual resources of the underlying volume. | [optional] 
**conditions** | [**list[K8sIoApiCoreV1PersistentVolumeClaimCondition]**](K8sIoApiCoreV1PersistentVolumeClaimCondition.md) | Current Condition of persistent volume claim. If underlying persistent volume is being resized then the Condition will be set to &#39;ResizeStarted&#39;. | [optional] 
**phase** | **str** | Phase represents the current phase of PersistentVolumeClaim. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



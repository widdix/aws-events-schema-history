# AWS Events Schema History

```
aws schemas list-schemas --registry-name aws.events --query 'Schemas[] | sort_by(@, &LastModified) | [][SchemaName, VersionCount, LastModified]' --output table
```

## Schemas

| Schema                                                         | Version | Created Date           |
| -------------------------------------------------------------- | -- -----| ---------------------- |
|  aws.emr@EMRStepStatusChange                                   | 1       |  2019-12-01T00:31:47Z  |
|  aws.health@AWSHealthAbuseEvent                                | 1       |  2019-12-01T00:31:47Z  |
|  aws.health@AWSHealthEvent                                     | 1       |  2019-12-01T00:31:47Z  |
|  aws.macie@MacieAlert                                          | 1       |  2019-12-01T00:31:47Z  |
|  aws.ecr@ECRImageScan                                          | 1       |  2019-12-01T00:31:48Z  |
|  aws.iotanalytics@AWSAPICallViaCloudTrail                      | 1       |  2019-12-01T00:31:48Z  |
|  aws.kms@KMSImportedKeyMaterialExpiration                      | 1       |  2019-12-01T00:31:48Z  |
|  aws.mediapackage@MediaPackageHarvestJobNotification           | 1       |  2019-12-01T00:31:48Z  |
|  aws.rds@RDSDBSnapshotEvent                                    | 1       |  2019-12-01T00:31:48Z  |
|  aws.s3@AWSAPICallViaCloudTrail                                | 1       |  2019-12-01T00:31:48Z  |
|  aws.autoscaling@EC2InstanceLaunchLifecycleAction              | 1       |  2019-12-01T00:31:49Z  |
|  aws.codebuild@AWSAPICallViaCloudTrail                         | 1       |  2019-12-01T00:31:49Z  |
|  aws.datasync@DataSyncAgentStateChange                         | 1       |  2019-12-01T00:31:49Z  |
|  aws.emr@EMRInstanceFleetStateChange                           | 1       |  2019-12-01T00:31:49Z  |
|  aws.glue@GlueJobRunStatus                                     | 1       |  2019-12-01T00:31:49Z  |
|  aws.mediapackage@MediaPackageKeyProviderNotification          | 1       |  2019-12-01T00:31:49Z  |
|  aws.ec2@AWSAPICallViaCloudTrail                               | 1       |  2019-12-01T00:31:50Z  |
|  aws.ec2@EC2InstanceStateChangeNotification                    | 1       |  2019-12-01T00:31:50Z  |
|  aws.sagemaker@SageMakerNotebookLifecycleConfigStateChange     | 1       |  2019-12-01T00:31:50Z  |
|  aws.ec2@EBSMultiVolumeSnapshotsCompletionStatus               | 1       |  2019-12-01T00:31:51Z  |
|  aws.ec2@EBSVolumeNotification                                 | 1       |  2019-12-01T00:31:51Z  |
|  aws.ecr@AWSAPICallViaCloudTrail                               | 1       |  2019-12-01T00:31:51Z  |
|  aws.kms@KMSCMKRotation                                        | 1       |  2019-12-01T00:31:51Z  |
|  aws.monitoring@AWSAPICallViaCloudTrail                        | 1       |  2019-12-01T00:31:51Z  |
|  aws.rds@RDSDBInstanceEvent                                    | 1       |  2019-12-01T00:31:51Z  |
|  aws.codepipeline@CodePipelinePipelineExecutionStateChange     | 1       |  2019-12-01T00:31:52Z  |
|  aws.ec2@EBSSnapshotNotification                               | 1       |  2019-12-01T00:31:52Z  |
|  aws.glue@GlueJobStateChange                                   | 1       |  2019-12-01T00:31:52Z  |
|  aws.opsworks@OpsWorksInstanceStateChange                      | 1       |  2019-12-01T00:31:52Z  |
|  aws.sagemaker@SageMakerEndpointConfigStateChange              | 1       |  2019-12-01T00:31:52Z  |
|  aws.codebuild@CodeBuildBuildPhaseChange                       | 1       |  2019-12-01T00:31:53Z  |
|  aws.datasync@DataSyncLocationStateChange                      | 1       |  2019-12-01T00:31:54Z  |
|  aws.ec2@EC2SpotInstanceInterruptionWarning                    | 1       |  2019-12-01T00:31:54Z  |
|  aws.opsworks@OpsWorksCommandStateChange                       | 1       |  2019-12-01T00:31:54Z  |
|  aws.securityhub@SecurityHubInsightResults                     | 1       |  2019-12-01T00:31:54Z  |
|  aws.cloudwatch@CloudWatchAlarmStateChange                     | 1       |  2019-12-01T00:31:55Z  |
|  aws.ecs@ECSServiceAction                                      | 1       |  2019-12-01T00:31:55Z  |
|  aws.glue@GlueDataCatalogDatabaseStateChange                   | 1       |  2019-12-01T00:31:55Z  |
|  aws.iotanalytics@IoTAnalyticsDataSetLifeCycleNotification     | 1       |  2019-12-01T00:31:55Z  |
|  aws.rds@RDSDBClusterEvent                                     | 1       |  2019-12-01T00:31:55Z  |
|  aws.sagemaker@SageMakerModelPackageStateChange                | 1       |  2019-12-01T00:31:55Z  |
|  aws.autoscaling@EC2InstanceLaunchUnsuccessful                 | 1       |  2019-12-01T00:31:56Z  |
|  aws.autoscaling@EC2InstanceTerminateSuccessful                | 1       |  2019-12-01T00:31:56Z  |
|  aws.autoscaling@EC2InstanceTerminateUnsuccessful              | 1       |  2019-12-01T00:31:56Z  |
|  aws.batch@AWSAPICallViaCloudTrail                             | 1       |  2019-12-01T00:31:56Z  |
|  aws.batch@BatchJobStateChange                                 | 1       |  2019-12-01T00:31:56Z  |
|  aws.codedeploy@CodeDeployDeploymentStateChangeNotification    | 1       |  2019-12-01T00:31:56Z  |
|  aws.codepipeline@CodePipelineActionExecutionStateChange       | 1       |  2019-12-01T00:31:56Z  |
|  aws.codepipeline@CodePipelineStageExecutionStateChange        | 1       |  2019-12-01T00:31:56Z  |
|  aws.datasync@DataSyncTaskExecutionStateChange                 | 1       |  2019-12-01T00:31:56Z  |
|  aws.datasync@DataSyncTaskStateChange                          | 1       |  2019-12-01T00:31:56Z  |
|  aws.dlm@DLMPolicyStateChange                                  | 1       |  2019-12-01T00:31:56Z  |
|  aws.ecr@ECRImageAction                                        | 1       |  2019-12-01T00:31:56Z  |
|  aws.ecs@ECSContainerInstanceStateChange                       | 1       |  2019-12-01T00:31:56Z  |
|  aws.ecs@ECSTaskStateChange                                    | 1       |  2019-12-01T00:31:56Z  |
|  aws.emr@EMRAutoScalingPolicyStateChange                       | 1       |  2019-12-01T00:31:56Z  |
|  aws.emr@EMRClusterStateChange                                 | 1       |  2019-12-01T00:31:56Z  |
|  aws.emr@EMRConfigurationError                                 | 1       |  2019-12-01T00:31:56Z  |
|  aws.emr@EMRInstanceGroupStateChange                           | 1       |  2019-12-01T00:31:56Z  |
|  aws.emr@EMRInstanceGroupStatusNotification                    | 1       |  2019-12-01T00:31:56Z  |
|  aws.gamelift@GameLiftMatchmakingEvent                         | 1       |  2019-12-01T00:31:56Z  |
|  aws.glue@AWSAPICallViaCloudTrail                              | 1       |  2019-12-01T00:31:56Z  |
|  aws.glue@GlueDataCatalogTableStateChange                      | 1       |  2019-12-01T00:31:56Z  |
|  aws.kms@AWSAPICallViaCloudTrail                               | 1       |  2019-12-01T00:31:56Z  |
|  aws.logs@AWSAPICallViaCloudTrail                              | 1       |  2019-12-01T00:31:56Z  |
|  aws.managedblockchain@ManagedBlockchainInvitationStatusChange | 1       |  2019-12-01T00:31:56Z  |
|  aws.managedblockchain@ManagedBlockchainProposalStatusChange   | 1       |  2019-12-01T00:31:56Z  |
|  aws.medialive@MediaLiveChannelAlert                           | 1       |  2019-12-01T00:31:56Z  |
|  aws.mediapackage@MediaPackageInputNotification                | 1       |  2019-12-01T00:31:56Z  |
|  aws.organizations@AWSServiceEventViaCloudTrail                | 1       |  2019-12-01T00:31:56Z  |
|  aws.rds@RDSDBParameterGroupEvent                              | 1       |  2019-12-01T00:31:56Z  |
|  aws.rds@RDSDBSecurityGroupEvent                               | 1       |  2019-12-01T00:31:56Z  |
|  aws.sagemaker@SageMakerAlgorithmStateChange                   | 1       |  2019-12-01T00:31:56Z  |
|  aws.sagemaker@SageMakerModelStateChange                       | 1       |  2019-12-01T00:31:56Z  |
|  aws.securityhub@SecurityHubFindingsCustomAction               | 1       |  2019-12-01T00:31:56Z  |
|  aws.signing@AWSConsoleSignInViaCloudTrail                     | 1       |  2019-12-01T00:31:56Z  |
|  aws.states@AWSAPICallViaCloudTrail                            | 1       |  2019-12-01T00:31:56Z  |
|  aws.states@StepFunctionsExecutionStatusChange                 | 1       |  2019-12-01T00:31:56Z  |
|  aws.transcribe@AWSAPICallViaCloudTrail                        | 1       |  2019-12-01T00:31:56Z  |
|  aws.transcribe@TranscribeJobStateChange                       | 1       |  2019-12-01T00:31:56Z  |
|  aws.trustedadvisor@TrustedAdvisorCheckItemRefreshNotification | 1       |  2019-12-01T00:31:56Z  |
|  aws.workspaces@WorkSpacesAccess                               | 1       |  2019-12-01T00:31:56Z  |
|  aws.autoscaling@EC2InstanceTerminateLifecycleAction           | 1       |  2019-12-01T00:31:57Z  |
|  aws.codebuild@AWSServiceEventViaCloudTrail                    | 1       |  2019-12-01T00:31:57Z  |
|  aws.ecs@AWSAPICallViaCloudTrail                               | 1       |  2019-12-01T00:31:57Z  |
|  aws.opsworks@OpsWorksAlert                                    | 1       |  2019-12-01T00:31:57Z  |
|  aws.rds@RDSDBClusterSnapshotEvent                             | 1       |  2019-12-01T00:31:57Z  |
|  aws.sagemaker@SageMakerHyperParameterTuningJobStateChange     | 1       |  2019-12-01T00:31:57Z  |
|  aws.sagemaker@SageMakerTransformJobStateChange                | 1       |  2019-12-01T00:31:57Z  |
|  aws.opsworks@OpsWorksDeploymentStateChange                    | 1       |  2019-12-01T00:31:58Z  |
|  aws.autoscaling@AWSAPICallViaCloudTrail                       | 1       |  2019-12-01T00:31:59Z  |
|  aws.codecommit@CodeCommitApprovalRuleTemplateChange           | 1       |  2019-12-01T00:31:59Z  |
|  aws.codecommit@CodeCommitCommentOnPullRequest                 | 1       |  2019-12-01T00:31:59Z  |
|  aws.codecommit@CodeCommitRepositoryStateChange                | 1       |  2019-12-01T00:31:59Z  |
|  aws.sagemaker@SageMakerEndpointStateChange                    | 1       |  2019-12-01T00:31:59Z  |
|  aws.sagemaker@SageMakerNotebookInstanceStateChange            | 1       |  2019-12-01T00:31:59Z  |
|  aws.securityhub@SecurityHubFindingsImported                   | 1       |  2019-12-01T00:31:59Z  |
|  aws.codecommit@CodeCommitCommentOnCommit                      | 1       |  2019-12-01T00:32:00Z  |
|  aws.sagemaker@SageMakerTrainingJobStateChange                 | 1       |  2019-12-01T00:32:00Z  |
|  aws.codecommit@CodeCommitPullRequestStateChange               | 1       |  2019-12-01T00:32:02Z  |
|  aws.qldb@QLDBLedgerStateChange                                | 1       |  2019-12-01T00:32:02Z  |
|  aws.codedeploy@CodeDeployInstanceStateChangeNotification      | 1       |  2019-12-01T00:32:03Z  |
|  aws.medialive@MediaLiveChannelStateChange                     | 1       |  2019-12-01T00:32:03Z  |
|  aws.dlm@AWSAPICallViaCloudTrail                               | 1       |  2019-12-01T00:32:04Z  |
|  aws.elasticloadbalancing@AWSAPICallViaCloudTrail              | 1       |  2019-12-01T00:32:04Z  |
|  aws.sagemaker@AWSAPICallViaCloudTrail                         | 1       |  2019-12-01T00:32:04Z  |
|  aws.autoscaling@EC2InstanceLaunchSuccessful                   | 1       |  2019-12-01T00:32:07Z  |
|  aws.kms@KMSCMKDeletion                                        | 1       |  2019-12-01T00:32:07Z  |
|  aws.codebuild@CodeBuildBuildStateChange                       | 1       |  2019-12-01T00:32:09Z  |
|  aws.athena@AthenaQueryStateChange                             | 1       |  2020-01-16T20:30:38Z  |
|  aws.ssm@CalendarStateChange                                   | 1       |  2020-01-16T20:30:38Z  |
|  aws.chime@ChimeVoiceConnectorStreamingStatus                  | 1       |  2020-01-16T20:30:39Z  |
|  aws.medialive@MediaLiveMultiplexAlert                         | 1       |  2020-01-16T20:30:39Z  |
|  aws.schemas@SchemaCreated                                     | 1       |  2020-01-16T20:30:39Z  |
|  aws.schemas@SchemaVersionCreated                              | 1       |  2020-01-16T20:30:39Z  |
|  aws.medialive@MediaLiveMultiplexStateChange                   | 1       |  2020-01-16T20:30:40Z  |
|  aws.tag@TagChangeOnResource                                   | 2       |  2020-01-16T20:30:40Z  |
|  aws.codecommit@AWSAPICallViaCloudTrail                        | 2       |  2020-01-16T20:30:43Z  |

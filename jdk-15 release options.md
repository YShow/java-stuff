<pre>
[Global flags ranges]
      int AVX3Threshold                                      [ 0                         ...                2147483647 ]                    {ARCH diagnostic} {default}
     intx AbortVMOnVMOperationTimeoutDelay                   [ 0                         ...       9223372036854775807 ]                         {diagnostic} {default}
      int ActiveProcessorCount                               [                           ...                           ]                            {product} {default}
    uintx AdaptiveSizeDecrementScaleFactor                   [ 1                         ...      18446744073709551615 ]                            {product} {default}
    uintx AdaptiveSizeMajorGCDecayTimeScale                  [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx AdaptiveSizePolicyCollectionCostMargin             [ 0                         ...                       100 ]                            {product} {default}
    uintx AdaptiveSizePolicyInitializingSteps                [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx AdaptiveSizePolicyOutputInterval                   [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx AdaptiveSizePolicyWeight                           [ 0                         ...                       100 ]                            {product} {default}
    uintx AdaptiveSizeThroughPutPolicy                       [ 0                         ...                         1 ]                            {product} {default}
    uintx AdaptiveTimeWeight                                 [ 0                         ...                       100 ]                            {product} {default}
     intx AliasLevel                                         [ 0                         ...                         3 ]                         {C2 product} {default}
     intx AllocateInstancePrefetchLines                      [ 1                         ...                        64 ]                            {product} {default}
     intx AllocatePrefetchDistance                           [ -9223372036854775808      ...       9223372036854775807 ]                            {product} {default}
     intx AllocatePrefetchInstr                              [ -9223372036854775808      ...       9223372036854775807 ]                            {product} {default}
     intx AllocatePrefetchLines                              [ 1                         ...                        64 ]                            {product} {default}
     intx AllocatePrefetchStepSize                           [ 1                         ...                       512 ]                            {product} {default}
     intx AllocatePrefetchStyle                              [ 0                         ...                         3 ]                            {product} {default}
     intx ArchiveRelocationMode                              [ 0                         ...                         2 ]                         {diagnostic} {default}
   size_t ArrayAllocatorMallocLimit                          [                           ...                           ]                       {experimental} {default}
     intx ArrayCopyLoadStoreMaxElem                          [ 0                         ...       9223372036854775807 ]                         {C2 product} {default}
     intx AutoBoxCacheMax                                    [ 0                         ...                2147483647 ]                         {C2 product} {default}
     intx BCEATraceLevel                                     [ 0                         ...                         3 ]                            {product} {default}
   size_t BaseFootPrintEstimate                              [ 0                         ...      18446744073709551615 ]                            {product} {default}
     intx BiasedLockingBulkRebiasThreshold                   [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx BiasedLockingBulkRevokeThreshold                   [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx BiasedLockingDecayTime                             [ 500                       ...       9223372036854775807 ]                            {product} {default}
     intx BiasedLockingStartupDelay                          [ 0                         ...                2147483640 ]                            {product} {default}
     intx BlockLayoutMinDiamondPercentage                    [ 0                         ...                       100 ]                         {C2 product} {default}
     intx CICompilerCount                                    [ 0                         ...                2147483647 ]                            {product} {ergonomic}
    uintx CodeCacheExpansionSize                             [ 32768                     ...      18446744073709551615 ]                         {pd product} {default}
    uintx CodeCacheMinBlockLength                            [ 1                         ...                       100 ]                      {pd diagnostic} {default}
     intx CompileThreshold                                   [ -9223372036854775808      ...       9223372036854775807 ]                         {pd product} {default}
   double CompileThresholdScaling                            [ 0.000                     ... 179769313486231570814527423731704356798070567525844996598917476803157260780028538760589558632766878171540458953514382464234321326889464182768467546703537516986049910576551282076245490090389328944075868508455133942304583236903222948165808559332123348274797826204144723168738177180919299881250404026184124858368.000 ]                           {product} {default}
      int CompilerDirectivesLimit                            [                           ...                           ]                         {diagnostic} {default}
     intx CompilerThreadPriority                             [ -2147483648               ...                2147483647 ]                            {product} {default}
     intx CompilerThreadStackSize                            [ 0                         ...          9007199254740991 ]                         {pd product} {default}
   size_t CompressedClassSpaceSize                           [ 1048576                   ...                3221225472 ]                            {product} {default}
     uint ConcGCThreads                                      [ 0                         ...                4294967295 ]                            {product} {ergonomic}
     intx ConditionalMoveLimit                               [ 0                         ...                2147483647 ]                      {C2 pd product} {default}
     intx ContendedPaddingWidth                              [ 0                         ...                      8192 ]                            {product} {default}
     intx DominatorSearchLimit                               [ 0                         ...                2147483647 ]                      {C2 diagnostic} {default}
     intx EliminateAllocationArraySizeLimit                  [ 0                         ...                2147483647 ]                         {C2 product} {default}
   size_t EpsilonMaxTLABSize                                 [ 1                         ...       9223372036854775807 ]                       {experimental} {default}
   size_t EpsilonMinHeapExpand                               [ 1                         ...       9223372036854775807 ]                       {experimental} {default}
   size_t EpsilonPrintHeapSteps                              [ 0                         ...       9223372036854775807 ]                       {experimental} {default}
   size_t EpsilonTLABDecayTime                               [ 1                         ...       9223372036854775807 ]                       {experimental} {default}
   double EpsilonTLABElasticity                              [ 1.000                     ... 179769313486231570814527423731704356798070567525844996598917476803157260780028538760589558632766878171540458953514382464234321326889464182768467546703537516986049910576551282076245490090389328944075868508455133942304583236903222948165808559332123348274797826204144723168738177180919299881250404026184124858368.000 ]                      {experimental} {default}
   size_t EpsilonUpdateCountersStep                          [ 1                         ...       9223372036854775807 ]                       {experimental} {default}
   size_t ErgoHeapSizeLimit                                  [ 0                         ...      18446744073709551615 ]                            {product} {default}
 uint64_t ErrorLogTimeout                                    [ 0                         ...          9223372036854775 ]                            {product} {default}
   double EscapeAnalysisTimeout                              [ 0.000                     ... 179769313486231570814527423731704356798070567525844996598917476803157260780028538760589558632766878171540458953514382464234321326889464182768467546703537516986049910576551282076245490090389328944075868508455133942304583236903222948165808559332123348274797826204144723168738177180919299881250404026184124858368.000 ]                        {C2 product} {default}
     intx FieldsAllocationStyle                              [ 0                         ...                         2 ]                            {product} {default}
     intx FreqInlineSize                                     [ 0                         ...                2147483647 ]                         {pd product} {default}
   size_t G1AdaptiveIHOPNumInitialSamples                    [ 1                         ...       9223372036854775807 ]                       {experimental} {default}
   double G1ConcMarkStepDurationMillis                       [ 1.000                     ... 179769313486231570814527423731704356798070567525844996598917476803157260780028538760589558632766878171540458953514382464234321326889464182768467546703537516986049910576551282076245490090389328944075868508455133942304583236903222948165808559332123348274797826204144723168738177180919299881250404026184124858368.000 ]                           {product} {default}
    uintx G1ConcRSHotCardLimit                               [ 0                         ...                       255 ]                            {product} {default}
   size_t G1ConcRSLogCacheSize                               [ 0                         ...                        27 ]                            {product} {default}
   size_t G1ConcRefinementGreenZone                          [ 0                         ...       9223372036854775807 ]                            {product} {default}
   size_t G1ConcRefinementRedZone                            [ 0                         ...       9223372036854775807 ]                            {product} {default}
    uintx G1ConcRefinementServiceIntervalMillis              [ 0                         ...                2147483647 ]                            {product} {default}
     uint G1ConcRefinementThreads                            [ 0                         ...                 268435455 ]                            {product} {ergonomic}
   size_t G1ConcRefinementThresholdStep                      [ 1                         ...      18446744073709551615 ]                            {product} {default}
   size_t G1ConcRefinementYellowZone                         [ 0                         ...       9223372036854775807 ]                            {product} {default}
    uintx G1ConfidencePercent                                [ 0                         ...                       100 ]                            {product} {default}
     intx G1ExpandByPercentOfAvailable                       [ 0                         ...                       100 ]                       {experimental} {default}
   size_t G1HeapRegionSize                                   [ 0                         ...                  33554432 ]                            {product} {ergonomic}
    uintx G1HeapWastePercent                                 [ 0                         ...                       100 ]                            {product} {default}
   double G1LastPLABAverageOccupancy                         [ 0.001                     ...                   100.000 ]                       {experimental} {default}
    uintx G1MaxNewSizePercent                                [ 0                         ...                       100 ]                       {experimental} {default}
    uintx G1MixedGCCountTarget                               [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx G1MixedGCLiveThresholdPercent                      [ 0                         ...                       100 ]                       {experimental} {default}
    uintx G1NewSizePercent                                   [ 0                         ...                       100 ]                       {experimental} {default}
    uintx G1OldCSetRegionThresholdPercent                    [ 0                         ...                       100 ]                       {experimental} {default}
    uintx G1PeriodicGCInterval                               [                           ...                           ]                         {manageable} {default}
   double G1PeriodicGCSystemLoadThreshold                    [ 0.000                     ...  18446744073709551616.000 ]                         {manageable} {default}
     intx G1RSetRegionEntries                                [ 0                         ...                 268435455 ]                            {product} {default}
   size_t G1RSetScanBlockSize                                [ 1                         ...      18446744073709551615 ]                            {product} {default}
     intx G1RSetSparseRegionEntries                          [ 0                         ...                 268435455 ]                            {product} {default}
     intx G1RSetUpdatingPauseTimePercent                     [ 0                         ...                       100 ]                            {product} {default}
   size_t G1RebuildRemSetChunkSize                           [ 4096                      ...                  33554432 ]                       {experimental} {default}
     uint G1RefProcDrainInterval                             [ 1                         ...                2147483647 ]                            {product} {default}
    uintx G1ReservePercent                                   [ 0                         ...                        50 ]                            {product} {default}
    uintx G1SATBBufferEnqueueingThresholdPercent             [ 0                         ...                       100 ]                            {product} {default}
   size_t G1SATBBufferSize                                   [ 1                         ...      18446744073709551615 ]                            {product} {default}
     intx G1SummarizeRSetStatsPeriod                         [ 0                         ...       9223372036854775807 ]                         {diagnostic} {default}
   size_t G1UpdateBufferSize                                 [ 1                         ...                1073741824 ]                            {product} {default}
    uintx G1YoungExpansionBufferPercent                      [ 0                         ...                       100 ]                       {experimental} {default}
    uintx GCDrainStackTargetSize                             [ 0                         ...                4294967295 ]                            {product} {ergonomic}
    uintx GCHeapFreeLimit                                    [ 0                         ...                       100 ]                            {product} {default}
    uintx GCLockerEdenExpansionPercent                       [ 0                         ...                       100 ]                            {product} {default}
    uintx GCLockerRetryAllocationCount                       [ 0                         ...      18446744073709551615 ]                         {diagnostic} {default}
    uintx GCPauseIntervalMillis                              [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx GCTimeLimit                                        [ 0                         ...                       100 ]                            {product} {default}
    uintx GCTimeRatio                                        [ 0                         ...                4294967295 ]                            {product} {default}
     intx GuaranteedSafepointInterval                        [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     uint HandshakeTimeout                                   [                           ...                           ]                         {diagnostic} {default}
   size_t HeapBaseMinAddress                                 [ 0                         ...      18446744073709551615 ]                         {pd product} {default}
    uintx HeapFirstMaximumCompactionCount                    [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx HeapMaximumCompactionInterval                      [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx HeapSearchSteps                                    [ 1                         ...      18446744073709551615 ]                            {product} {default}
   size_t HeapSizePerGCThread                                [ 4096                      ...      18446744073709551615 ]                            {product} {default}
     intx HotMethodDetectionLimit                            [ 1                         ...                2147483647 ]                         {diagnostic} {default}
    uintx IncreaseFirstTierCompileThresholdAt                [ 0                         ...                        99 ]                            {product} {default}
     intx InitArrayShortSize                                 [ 0                         ...       9223372036854775807 ]                      {pd diagnostic} {default}
   size_t InitialBootClassLoaderMetaspaceSize                [ 30720                     ...       2305843009213693951 ]                            {product} {default}
    uintx InitialCodeCacheSize                               [ 4096                      ...      18446744073709551615 ]                         {pd product} {default}
   size_t InitialHeapSize                                    [ 0                         ...      18446744073709551615 ]                            {product} {ergonomic}
    uintx InitialRAMFraction                                 [ 1                         ...      18446744073709551615 ]                            {product} {default}
   double InitialRAMPercentage                               [ 0.000                     ...                   100.000 ]                            {product} {default}
    uintx InitialSurvivorRatio                               [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx InitialTenuringThreshold                           [ 0                         ...                        16 ]                            {product} {default}
    uintx InitiatingHeapOccupancyPercent                     [ 0                         ...                       100 ]                            {product} {default}
     intx InlineFrequencyCount                               [ 0                         ...                2147483647 ]                      {pd diagnostic} {default}
     intx InlineSmallCode                                    [ 0                         ...                2147483647 ]                         {pd product} {default}
     intx InteriorEntryAlignment                             [ -9223372036854775808      ...       9223372036854775807 ]                      {C2 pd product} {default}
     intx InterpreterProfilePercentage                       [ 0                         ...                       100 ]                            {product} {default}
     intx JVMCICounterSize                                   [ 0                         ...                2147483647 ]                 {JVMCI experimental} {default}
     intx JVMCIHostThreads                                   [ 1                         ...                2147483647 ]                 {JVMCI experimental} {default}
     intx JVMCINMethodSizeLimit                              [                           ...                           ]                 {JVMCI experimental} {default}
     intx JVMCIThreads                                       [ 1                         ...                2147483647 ]                 {JVMCI experimental} {default}
     intx JVMCITraceLevel                                    [                           ...                           ]                 {JVMCI experimental} {default}
     intx JavaPriority10_To_OSPriority                       [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority1_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority2_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority3_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority4_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority5_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority6_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority7_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority8_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
     intx JavaPriority9_To_OSPriority                        [ -1                        ...                       127 ]                            {product} {default}
   size_t LargePageHeapSizeThreshold                         [ 0                         ...      18446744073709551615 ]                            {product} {default}
   size_t LargePageSizeInBytes                               [ 0                         ...      18446744073709551615 ]                            {product} {default}
     intx LiveNodeCountInliningCutoff                        [ 0                         ...                 536870911 ]                         {C2 product} {default}
    uintx LogEventsBufferEntries                             [ 1                         ...                   1048576 ]                         {diagnostic} {default}
     intx LoopMaxUnroll                                      [ 0                         ...                2147483647 ]                         {C2 product} {default}
     intx LoopOptsCount                                      [ 5                         ...                        43 ]                         {C2 product} {default}
     intx LoopPercentProfileLimit                            [ 10                        ...                       100 ]                      {C2 pd product} {default}
    uintx LoopStripMiningIter                                [ 0                         ...                4294967295 ]                         {C2 product} {default}
    uintx LoopStripMiningIterShortLoop                       [ 0                         ...                4294967295 ]                         {C2 product} {default}
     intx LoopUnrollLimit                                    [ 0                         ...                 536870911 ]                      {C2 pd product} {default}
     intx LoopUnrollMin                                      [ 0                         ...                2147483647 ]                         {C2 product} {default}
    uintx MallocMaxTestWords                                 [ 0                         ...      18446744073709551615 ]                         {diagnostic} {default}
   size_t MarkStackSize                                      [ 0                         ...      18446744073709551615 ]                            {product} {ergonomic}
   size_t MarkStackSizeMax                                   [ 1                         ...                2147483646 ]                            {product} {default}
     uint MarkSweepAlwaysCompactCount                        [ 1                         ...                4294967295 ]                            {product} {default}
    uintx MarkSweepDeadRatio                                 [ 0                         ...                       100 ]                            {product} {default}
     intx MaxBCEAEstimateLevel                               [ 0                         ...                2147483647 ]                            {product} {default}
     intx MaxBCEAEstimateSize                                [ 0                         ...                2147483647 ]                            {product} {default}
 uint64_t MaxDirectMemorySize                                [ 0                         ...       9223372036854775807 ]                            {product} {default}
    uintx MaxGCMinorPauseMillis                              [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx MaxGCPauseMillis                                   [ 1                         ...      18446744073709551614 ]                            {product} {default}
    uintx MaxHeapFreeRatio                                   [ 0                         ...                       100 ]                         {manageable} {default}
   size_t MaxHeapSize                                        [ 0                         ...      18446744073709551615 ]                            {product} {ergonomic}
     intx MaxInlineLevel                                     [ 0                         ...                2147483647 ]                            {product} {default}
     intx MaxInlineSize                                      [ 0                         ...                2147483647 ]                            {product} {default}
     intx MaxJNILocalCapacity                                [ -9223372036854775808      ...       9223372036854775807 ]                            {product} {default}
     intx MaxJavaStackTraceDepth                             [ 0                         ...                1073741823 ]                            {product} {default}
     intx MaxJumpTableSize                                   [ 0                         ...       9223372036854775807 ]                         {C2 product} {default}
     intx MaxJumpTableSparseness                             [ 0                         ...       2305843009213693951 ]                         {C2 product} {default}
     intx MaxLabelRootDepth                                  [ 100                       ...                2147483647 ]                         {C2 product} {default}
     intx MaxLoopPad                                         [ 0                         ...                2147483647 ]                         {C2 product} {default}
   size_t MaxMetaspaceExpansion                              [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx MaxMetaspaceFreeRatio                              [ 0                         ...                       100 ]                            {product} {default}
   size_t MaxMetaspaceSize                                   [ 0                         ...      18446744073709551615 ]                            {product} {default}
   size_t MaxNewSize                                         [ 0                         ...      18446744073709551615 ]                            {product} {ergonomic}
     intx MaxNodeLimit                                       [ 1000                      ...                 715827882 ]                         {C2 product} {default}
 uint64_t MaxRAM                                             [ 0                         ...      18446744073709551615 ]                         {pd product} {default}
    uintx MaxRAMFraction                                     [ 1                         ...      18446744073709551615 ]                            {product} {default}
   double MaxRAMPercentage                                   [ 0.000                     ...                   100.000 ]                            {product} {default}
     intx MaxRecursiveInlineLevel                            [ 0                         ...                2147483647 ]                            {product} {default}
    uintx MaxTenuringThreshold                               [ 0                         ...                        16 ]                            {product} {default}
     intx MaxTrivialSize                                     [ 0                         ...                2147483647 ]                            {product} {default}
     intx MaxVectorSize                                      [ 0                         ...                2147483647 ]                         {C2 product} {default}
   size_t MetaspaceSize                                      [ 0                         ...      18446744073709551615 ]                         {pd product} {default}
     intx MethodProfileWidth                                 [                           ...                           ]                 {JVMCI experimental} {default}
   size_t MinHeapDeltaBytes                                  [ 0                         ...      18446744073709551615 ]                            {product} {ergonomic}
    uintx MinHeapFreeRatio                                   [ 0                         ...                       100 ]                         {manageable} {default}
   size_t MinHeapSize                                        [ 0                         ...      18446744073709551615 ]                            {product} {ergonomic}
     intx MinInliningThreshold                               [ 0                         ...                2147483647 ]                            {product} {default}
     intx MinJumpTableSize                                   [ 0                         ...       9223372036854775807 ]                      {C2 pd product} {default}
   size_t MinMetaspaceExpansion                              [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx MinMetaspaceFreeRatio                              [ 0                         ...                        99 ]                            {product} {default}
     intx MinPassesBeforeFlush                               [ 0                         ...       9223372036854775807 ]                         {diagnostic} {default}
    uintx MinRAMFraction                                     [ 1                         ...      18446744073709551615 ]                            {product} {default}
   double MinRAMPercentage                                   [ 0.000                     ...                   100.000 ]                            {product} {default}
    uintx MinSurvivorRatio                                   [ 3                         ...      18446744073709551615 ]                            {product} {default}
   size_t MinTLABSize                                        [ 1                         ...       9223372036854775807 ]                            {product} {default}
     intx MonitorBound                                       [ 0                         ...                2147483647 ]                            {product} {default}
     intx MonitorUsedDeflationThreshold                      [ 0                         ...                       100 ]                       {experimental} {default}
     intx MultiArrayExpandLimit                              [ 0                         ...                2147483647 ]                         {C2 product} {default}
    uintx NUMAChunkResizeWeight                              [ 0                         ...                       100 ]                            {product} {default}
   size_t NUMAInterleaveGranularity                          [ 4096                      ...             8796093022208 ]                            {product} {default}
    uintx NUMAPageScanRate                                   [ 0                         ...      18446744073709551615 ]                            {product} {default}
   size_t NUMASpaceResizeRate                                [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx NewRatio                                           [ 0                         ...      18446744073709551614 ]                            {product} {default}
   size_t NewSize                                            [ 0                         ...      18446744073709551615 ]                            {product} {default}
   size_t NewSizeThreadIncrease                              [ 0                         ...      18446744073709551615 ]                         {pd product} {default}
     intx NmethodSweepActivity                               [ 0                         ...                      2000 ]                            {product} {default}
     intx NodeLimitFudgeFactor                               [ -9223372036854775808      ...       9223372036854775807 ]                         {C2 product} {default}
    uintx NonNMethodCodeHeapSize                             [ 4096                      ...      18446744073709551615 ]                         {pd product} {ergonomic}
    uintx NonProfiledCodeHeapSize                            [ 0                         ...      18446744073709551615 ]                         {pd product} {ergonomic}
     intx NumberOfLoopInstrToAlign                           [ 0                         ...                2147483647 ]                         {C2 product} {default}
     intx ObjectAlignmentInBytes                             [ 8                         ...                       256 ]                       {lp64_product} {default}
   double ObjectCountCutOffPercent                           [ 0.000                     ...                   100.000 ]                       {experimental} {default}
   size_t OldPLABSize                                        [ 0                         ...      18446744073709551615 ]                            {product} {default}
   size_t OldSize                                            [ 0                         ...      18446744073709551615 ]                            {product} {default}
     intx OnStackReplacePercentage                           [ -9223372036854775808      ...       9223372036854775807 ]                         {pd product} {default}
     intx OptoLoopAlignment                                  [ 1                         ...                        16 ]                         {pd product} {default}
    uintx PLABWeight                                         [ 0                         ...                       100 ]                            {product} {default}
      int ParGCArrayScanChunk                                [ 1                         ...                 715827882 ]                            {product} {default}
    uintx ParallelGCBufferWastePct                           [ 0                         ...                       100 ]                            {product} {default}
     uint ParallelGCThreads                                  [ 0                         ...                4294967295 ]                            {product} {default}
   size_t ParallelOldDeadWoodLimiterMean                     [ 0                         ...                       100 ]                            {product} {default}
   size_t ParallelOldDeadWoodLimiterStdDev                   [ 0                         ...                       100 ]                            {product} {default}
     intx PartialPeelNewPhiDelta                             [ 0                         ...                2147483647 ]                         {C2 product} {default}
    uintx PausePadding                                       [ 0                         ...                4294967295 ]                            {product} {default}
     intx PerBytecodeRecompilationCutoff                     [ -1                        ...       9223372036854775807 ]                            {product} {default}
     intx PerBytecodeTrapLimit                               [ 0                         ...                2147483647 ]                            {product} {default}
     intx PerMethodRecompilationCutoff                       [ -1                        ...       9223372036854775807 ]                            {product} {default}
     intx PerMethodSpecTrapLimit                             [ 0                         ...                2147483647 ]                       {experimental} {default}
     intx PerMethodTrapLimit                                 [ 0                         ...                2147483647 ]                            {product} {default}
     intx PerfDataMemorySize                                 [ 128                       ...                   2097152 ]                            {product} {default}
     intx PerfDataSamplingInterval                           [ 10                        ...                2147483647 ]                            {product} {default}
     intx PerfMaxStringConstLength                           [ 32                        ...                     32768 ]                            {product} {default}
   size_t PreTouchParallelChunkSize                          [ 1                         ...       9223372036854775807 ]                            {product} {default}
     intx PrefetchCopyIntervalInBytes                        [ -1                        ...                2147483647 ]                            {product} {default}
     intx PrefetchFieldsAhead                                [ -1                        ...                2147483647 ]                            {product} {default}
     intx PrefetchScanIntervalInBytes                        [ -1                        ...                2147483647 ]                            {product} {default}
   size_t PretenureSizeThreshold                             [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx ProcessDistributionStride                          [ 0                         ...                4294967295 ]                            {product} {default}
     intx ProfileMaturityPercentage                          [ 0                         ...                       100 ]                            {product} {default}
    uintx ProfiledCodeHeapSize                               [ 0                         ...      18446744073709551615 ]                         {pd product} {ergonomic}
    uintx PromotedPadding                                    [ 0                         ...                4294967295 ]                            {product} {default}
    uintx QueuedAllocationWarningCount                       [ 0                         ...      18446744073709551615 ]                            {product} {default}
      int RTMAbortRatio                                      [ 0                         ...                       100 ]                  {ARCH experimental} {default}
      int RTMAbortThreshold                                  [ 0                         ...                2147483647 ]                  {ARCH experimental} {default}
     intx RTMLockingCalculationDelay                         [                           ...                           ]                  {ARCH experimental} {default}
      int RTMLockingThreshold                                [ 0                         ...                2147483647 ]                  {ARCH experimental} {default}
      int RTMRetryCount                                      [ 0                         ...                2147483647 ]                       {ARCH product} {default}
      int RTMSpinLoopCount                                   [ 0                         ...                2147483647 ]                  {ARCH experimental} {default}
      int RTMTotalCountIncrRate                              [ 1                         ...                2147483647 ]                  {ARCH experimental} {default}
     intx RefDiscoveryPolicy                                 [ 0                         ...                         1 ]                            {product} {default}
   size_t ReferencesPerThread                                [                           ...                           ]                       {experimental} {default}
    uintx ReservedCodeCacheSize                              [ 4096                      ...      18446744073709551615 ]                         {pd product} {ergonomic}
     intx SafepointTimeoutDelay                              [ 0                         ...             9223372036854 ]                            {product} {default}
     intx ScavengeRootsInCode                                [ 0                         ...                         2 ]                         {diagnostic} {default}
     intx SelfDestructTimer                                  [ 0                         ...       9223372036854775807 ]                            {product} {default}
   size_t SharedBaseAddress                                  [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx SharedSymbolTableBucketSize                        [ 2                         ...                       246 ]                            {product} {default}
    uintx ShenandoahAllocSpikeFactor                         [ 0                         ...                       100 ]                       {experimental} {default}
     intx ShenandoahAllocationStallThreshold                 [                           ...                           ]                         {diagnostic} {default}
    uintx ShenandoahAllocationThreshold                      [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahCodeRootsStyle                           [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahControlIntervalAdjustPeriod              [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahControlIntervalMax                       [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahControlIntervalMin                       [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahCriticalFreeThreshold                    [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahEvacAssist                               [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahEvacReserve                              [ 1                         ...                       100 ]                       {experimental} {default}
   double ShenandoahEvacWaste                                [ 1.000                     ...                   100.000 ]                       {experimental} {default}
    uintx ShenandoahFullGCThreshold                          [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahGarbageThreshold                         [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahGuaranteedGCInterval                     [                           ...                           ]                       {experimental} {default}
   size_t ShenandoahHeapRegionSize                           [                           ...                           ]                       {experimental} {default}
     intx ShenandoahHumongousThreshold                       [ 1                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahImmediateThreshold                       [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahInitFreeThreshold                        [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahLearningSteps                            [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahMarkLoopStride                           [                           ...                           ]                       {experimental} {default}
     intx ShenandoahMarkScanPrefetch                         [ 0                         ...                       256 ]                       {experimental} {default}
   size_t ShenandoahMaxRegionSize                            [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahMergeUpdateRefsMaxGap                    [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahMergeUpdateRefsMinGap                    [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahMinFreeThreshold                         [ 0                         ...                       100 ]                       {experimental} {default}
   size_t ShenandoahMinRegionSize                            [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahPacingCycleSlack                         [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahPacingIdleSlack                          [ 0                         ...                       100 ]                       {experimental} {default}
    uintx ShenandoahPacingMaxDelay                           [                           ...                           ]                       {experimental} {default}
   double ShenandoahPacingSurcharge                          [ 1.000                     ...                   100.000 ]                       {experimental} {default}
    uintx ShenandoahParallelRegionStride                     [                           ...                           ]                       {experimental} {default}
     uint ShenandoahParallelSafepointThreads                 [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahRefProcFrequency                         [                           ...                           ]                       {experimental} {default}
      int ShenandoahRegionSamplingRate                       [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahSATBBufferFlushInterval                  [                           ...                           ]                       {experimental} {default}
   size_t ShenandoahSATBBufferSize                           [ 1                         ...      18446744073709551615 ]                       {experimental} {default}
   size_t ShenandoahTargetNumRegions                         [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahUncommitDelay                            [                           ...                           ]                       {experimental} {default}
    uintx ShenandoahUnloadClassesFrequency                   [                           ...                           ]                       {experimental} {default}
     intx ShenandoahVerifyLevel                              [                           ...                           ]                         {diagnostic} {default}
   size_t SoftMaxHeapSize                                    [ 0                         ...      18446744073709551615 ]                         {manageable} {ergonomic}
     intx SoftRefLRUPolicyMSPerMB                            [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx SpecTrapLimitExtraEntries                          [                           ...                           ]                       {experimental} {default}
     intx StackRedPages                                      [ 1                         ...                         3 ]                         {pd product} {default}
     intx StackReservedPages                                 [ 0                         ...                        11 ]                         {pd product} {default}
     intx StackShadowPages                                   [ 10                        ...                        50 ]                         {pd product} {default}
     intx StackYellowPages                                   [ 2                         ...                         7 ]                         {pd product} {default}
    uintx StartAggressiveSweepingAt                          [ 0                         ...                       100 ]                            {product} {default}
    uintx StringDeduplicationAgeThreshold                    [ 1                         ...                        15 ]                            {product} {default}
    uintx StringTableSize                                    [ 128                       ...                  16777216 ]                            {product} {default}
     intx SurvivorAlignmentInBytes                           [ 8                         ...                       256 ]                       {experimental} {default}
    uintx SurvivorPadding                                    [ 0                         ...                4294967295 ]                            {product} {default}
    uintx SurvivorRatio                                      [ 1                         ...      18446744073709551613 ]                            {product} {default}
     intx SuspendRetryCount                                  [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx SuspendRetryDelay                                  [ 0                         ...       9223372036854775807 ]                            {product} {default}
    uintx SymbolTableSize                                    [ 1024                      ...                  16777216 ]                       {experimental} {default}
    uintx TLABAllocationWeight                               [ 0                         ...                       100 ]                            {product} {default}
    uintx TLABRefillWasteFraction                            [ 1                         ...                4294967295 ]                            {product} {default}
   size_t TLABSize                                           [ 0                         ...      18446744073709551615 ]                            {product} {default}
    uintx TLABWasteIncrement                                 [ 0                         ...                2147483647 ]                            {product} {default}
    uintx TLABWasteTargetPercent                             [ 1                         ...                       100 ]                            {product} {default}
    uintx TargetPLABWastePct                                 [ 1                         ...                       100 ]                            {product} {default}
    uintx TargetSurvivorRatio                                [ 0                         ...                       100 ]                            {product} {default}
    uintx TenuredGenerationSizeIncrement                     [ 0                         ...                       100 ]                            {product} {default}
    uintx TenuredGenerationSizeSupplement                    [ 0                         ...                       100 ]                            {product} {default}
    uintx TenuredGenerationSizeSupplementDecay               [ 1                         ...      18446744073709551615 ]                            {product} {default}
     intx ThreadPriorityPolicy                               [ 0                         ...                         1 ]                            {product} {default}
     intx ThreadStackSize                                    [ 0                         ...                   1048576 ]                         {pd product} {default}
    uintx ThresholdTolerance                                 [ 0                         ...                       100 ]                            {product} {default}
     intx Tier0AOTBackEdgeThreshold                          [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier0AOTCompileThreshold                           [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier0AOTInvocationThreshold                        [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier0AOTMinInvocationThreshold                     [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier0BackedgeNotifyFreqLog                         [ 0                         ...                        30 ]                            {product} {default}
     intx Tier0Delay                                         [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier0InvokeNotifyFreqLog                           [ 0                         ...                        30 ]                            {product} {default}
     intx Tier0ProfilingStartPercentage                      [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier23InlineeNotifyFreqLog                         [ 0                         ...                        30 ]                            {product} {default}
     intx Tier2BackEdgeThreshold                             [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier2BackedgeNotifyFreqLog                         [ 0                         ...                        30 ]                            {product} {default}
     intx Tier2CompileThreshold                              [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier2InvokeNotifyFreqLog                           [ 0                         ...                        30 ]                            {product} {default}
     intx Tier3AOTBackEdgeThreshold                          [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3AOTCompileThreshold                           [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3AOTInvocationThreshold                        [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3AOTMinInvocationThreshold                     [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3BackEdgeThreshold                             [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3BackedgeNotifyFreqLog                         [ 0                         ...                        30 ]                            {product} {default}
     intx Tier3CompileThreshold                              [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3DelayOff                                      [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3DelayOn                                       [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3InvocationThreshold                           [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3InvokeNotifyFreqLog                           [ 0                         ...                        30 ]                            {product} {default}
     intx Tier3LoadFeedback                                  [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier3MinInvocationThreshold                        [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier40BackEdgeThreshold                            [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier40CompileThreshold                             [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier40InvocationThreshold                          [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier40MinInvocationThreshold                       [ 0                         ...                2147483647 ]                         {diagnostic} {default}
     intx Tier4BackEdgeThreshold                             [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier4CompileThreshold                              [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier4InvocationThreshold                           [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier4LoadFeedback                                  [ 0                         ...                2147483647 ]                            {product} {default}
     intx Tier4MinInvocationThreshold                        [ 0                         ...                2147483647 ]                            {product} {default}
     intx TieredCompileTaskTimeout                           [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx TieredRateUpdateMaxTime                            [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx TieredRateUpdateMinTime                            [ 0                         ...       9223372036854775807 ]                            {product} {default}
     intx TieredStopAtLevel                                  [ 0                         ...                         4 ]                            {product} {default}
     intx TrackedInitializationLimit                         [ 0                         ...                     65535 ]                         {C2 product} {default}
     intx TypeProfileArgsLimit                               [ 0                         ...                        16 ]                            {product} {default}
    uintx TypeProfileLevel                                   [ 0                         ...      18446744073709551615 ]                         {pd product} {default}
     intx TypeProfileMajorReceiverPercent                    [ 0                         ...                       100 ]                         {C2 product} {default}
     intx TypeProfileParmsLimit                              [ -1                        ...                        64 ]                            {product} {default}
     intx TypeProfileWidth                                   [ 0                         ...                         8 ]                            {product} {default}
     intx UnguardOnExecutionViolation                        [ 0                         ...                         2 ]                            {product} {default}
     intx UseAVX                                             [ 0                         ...                        99 ]                       {ARCH product} {default}
      int UseBootstrapCallInfo                               [                           ...                           ]                         {diagnostic} {default}
     intx UseSSE                                             [ 0                         ...                        99 ]                            {product} {default}
     intx VMThreadPriority                                   [ -1                        ...                       127 ]                            {product} {default}
     intx VMThreadStackSize                                  [ 0                         ...          9007199254740991 ]                         {pd product} {default}
     intx ValueMapInitialSize                                [ 1                         ...                     32768 ]                         {C1 product} {default}
     intx ValueMapMaxLoopSize                                [ 0                         ...                       128 ]                         {C1 product} {default}
     intx ValueSearchLimit                                   [ 0                         ...                2147483647 ]                         {C2 product} {default}
     intx VerifyGCLevel                                      [ 0                         ...                         1 ]                         {diagnostic} {default}
    uintx VerifyGCStartAt                                    [ 0                         ...      18446744073709551615 ]                         {diagnostic} {default}
    uintx WorkStealingHardSpins                              [                           ...                           ]                       {experimental} {default}
    uintx WorkStealingSleepMillis                            [                           ...                           ]                       {experimental} {default}
    uintx WorkStealingSpinToYieldRatio                       [                           ...                           ]                       {experimental} {default}
    uintx WorkStealingYieldsBeforeSleep                      [                           ...                           ]                       {experimental} {default}
    uintx YoungGenerationSizeIncrement                       [ 0                         ...                       100 ]                            {product} {default}
    uintx YoungGenerationSizeSupplement                      [ 0                         ...                       100 ]                            {product} {default}
    uintx YoungGenerationSizeSupplementDecay                 [ 1                         ...      18446744073709551615 ]                            {product} {default}
   size_t YoungPLABSize                                      [ 0                         ...      18446744073709551615 ]                            {product} {default}
   double ZAllocationSpikeTolerance                          [                           ...                           ]                       {experimental} {default}
     uint ZCollectionInterval                                [                           ...                           ]                       {experimental} {default}
   double ZFragmentationLimit                                [                           ...                           ]                       {experimental} {default}
   size_t ZMarkStackSpaceLimit                               [ 33554432                  ...             1099511627776 ]                       {experimental} {default}
     uint ZStatisticsInterval                                [ 1                         ...                4294967295 ]                         {diagnostic} {default}
    uintx ZUncommitDelay                                     [                           ...                           ]                       {experimental} {default}
     intx hashCode                                           [                           ...                           ]                       {experimental} {default}
[JVMCI properties]
jvmci.Compiler = null                                                     [String]
          Selects the system compiler. This must match the getCompilerName() value returned by a jdk.vm.ci.runtime.JVMCICompilerFactory provider. An empty string or the value "null" selects a compiler that will raise an exception upon receiving a compilation request.
jvmci.InitTimer = false                                                  [Boolean]
          Specifies if initialization timing is enabled.
jvmci.PrintConfig := false                                               [Boolean]
          Prints VM configuration available via JVMCI.
jvmci.AuditHandles = false                                               [Boolean]
          Record stack trace along with scoped foreign object reference wrappers to debug issue with a wrapper being used after its scope has closed.
jvmci.TraceMethodDataFilter = null                                        [String]
          Enables tracing of profiling info when read by JVMCI.
          Empty value: trace all methods
          Non-empty value: trace methods whose fully qualified name contains the value.
jvmci.UseProfilingInformation = true                                     [Boolean]
          
[Graal properties]
graal.AOTInliningDepthToSizeRate = 2.5                                    [Double]
graal.AOTInliningSizeMaximum = 300                                       [Integer]
graal.AOTInliningSizeMinimum = 50                                        [Integer]
graal.ASMInstructionProfiling = null                                      [String]
          Enables instruction profiling on assembler level. Valid values are a
          comma separated list of supported instructions. Compare with subclasses
          of Assembler.InstructionCounter.
graal.AbortOnBenchmarkCounterOverflow = false                            [Boolean]
          Abort VM with SIGILL if benchmark counters controlled by the
          (Generic|Timed|Benchmark)DynamicCounters
          option overflow. This feature is only supported on AMD64.
          WARNING: No descriptive error message will be printed! In case of an overflow,
          manual inspection of the emitted code is required.
graal.AggregatedMetricsFile = null                                        [String]
          File to which aggregated metrics are dumped at shutdown. A CSV format
          is used if the file ends with .csv otherwise a more human readable
          format is used. If not specified, metrics are dumped to the console.
graal.AlwaysInlineIntrinsics = false                                     [Boolean]
          Unconditionally inline intrinsics
graal.AlwaysInlineVTableStubs = false                                    [Boolean]
graal.BenchmarkCountersDumpDynamic = true                                [Boolean]
          Dump dynamic counters
graal.BenchmarkCountersDumpStatic = false                                [Boolean]
          Dump static counters
graal.BenchmarkCountersFile = null                                        [String]
          File to which benchmark counters are dumped. A CSV format is used if
          the file ends with .csv otherwise a more human readable format is used.
          The fields in the CSV format are: category, group, name, value
graal.BenchmarkDynamicCounters = null                                     [String]
          Turn on the benchmark counters. The format of this option is:
          
            (err|out),start pattern,end pattern
            
          Start counting when the start pattern matches on the given stream and stop when the end pattern occurs.
          You can use "~" to match 1 or more digits.
          Examples:
          
            err, starting =====, PASSED in
            out,Iteration ~ (~s) begins:,Iteration ~ (~s) ends:
            
          The first pattern matches DaCapo output and the second matches SPECjvm2008 output.
          
          As a more detailed example, here are the options to use for getting statistics
          about allocations within the DaCapo pmd benchmark:
          
            -XX:JVMCICounterSize=<value> -XX:-JVMCICountersExcludeCompiler \
            -Dgraal.BenchmarkDynamicCounters="err, starting ====, PASSED in " \
            -Dgraal.ProfileAllocations=true
            
          The JVMCICounterSize value depends on the granularity of the profiling -
          10000 should be sufficient. Omit JVMCICountersExcludeCompiler to exclude
          counting allocations on the compiler threads.
          The counters can be further configured by the ProfileAllocationsContext option.
          
          We highly recommend the use of -Dgraal.AbortOnBenchmarkCounterOverflow=true to
          detect counter overflows eagerly.
graal.BootstrapInitializeOnly = false                                    [Boolean]
          Do not compile anything on bootstrap but just initialize the compiler.
graal.BootstrapTimeout = 15.0                                             [Double]
          Maximum time in minutes to spend bootstrapping (0 to disable this
          limit).
graal.BootstrapWatchDogCriticalRateRatio = 0.25                           [Double]
          Ratio of the maximum compilation rate below which the bootstrap
          compilation rate must not fall (0 or less disables monitoring).
graal.CanOmitFrame = true                                                [Boolean]
graal.CanonicalGraphStringsCheckConstants = false                        [Boolean]
          Exclude virtual nodes when dumping canonical text for graphs.
graal.CanonicalGraphStringsExcludeVirtuals = true                        [Boolean]
          Exclude virtual nodes when dumping canonical text for graphs.
graal.CanonicalGraphStringsRemoveIdentities = true                       [Boolean]
          Attempts to remove object identity hashes when dumping canonical text
          for graphs.
graal.ClearMetricsAfterBootstrap = false                                 [Boolean]
          Clear the debug metrics after bootstrap.
graal.CompilationBailoutAsFailure = false                                [Boolean]
          Treat compilation bailouts like compilation failures.
graal.CompilationCountLimit = 0                                          [Integer]
          The number of compilations allowed for any method before the VM exits
          (a value of 0 means there is no limit).
graal.CompilationExpirationPeriod = 300                                  [Integer]
          Time limit in seconds before a compilation expires (0 to disable the
          limit). The compilation alarm will be implicitly disabled if assertions
          are enabled.
graal.CompilationFailureAction = Silent                                   [String]
          Specifies the action to take when compilation fails.
          The accepted values are:
              Silent - Print nothing to the console.
               Print - Print a stack trace to the console.
            Diagnose - Retry the compilation with extra diagnostics.
              ExitVM - Same as Diagnose except that the VM process exits after retrying.
graal.CompilationWatchDogStackTraceInterval = 60.0                        [Double]
          Interval in seconds between a watch dog reporting stack traces for long
          running compilations.
graal.CompilationWatchDogStartDelay = 0.0                                 [Double]
          Delay in seconds before watch dog monitoring a compilation (0 disables
          monitoring).
graal.CompileGraalWithC1Only = true                                      [Boolean]
          In tiered mode compile Graal and JVMCI using optimized first tier code.
graal.CompilerConfiguration = null                                        [String]
          Names the compiler configuration to use. If omitted, the compiler
          configuration with the highest auto-selection priority is used. To see
          the set of available configurations, supply the value 'help' to this
          option.
graal.ConditionalElimination = true                                      [Boolean]
graal.ConditionalEliminationMaxIterations = 4                            [Integer]
graal.Count = null                                                        [String]
          Pattern for specifying scopes in which counters are enabled. See the
          Dump option for the pattern syntax. An empty value enables all counters
          unconditionally.
graal.Counters = null                                                     [String]
          Comma separated names of counters that are enabled irrespective of the
          value for Count option. An empty value enables all counters
          unconditionally.
graal.CrashAt = null                                                      [String]
          Pattern for method(s) that will trigger an exception when compiled.
          This option exists to test handling compilation crashes gracefully. See
          the MethodFilter option for the pattern syntax. A ':Bailout' suffix
          will raise a bailout exception and a ':PermanentBailout' suffix will
          raise a permanent bailout exception.
graal.DebugStubsAndSnippets = false                                      [Boolean]
          Enable debug output for stub code generation and snippet preparation.
graal.DeoptALot = false                                                  [Boolean]
graal.DeoptAfterOSR = true                                               [Boolean]
          Deoptimize OSR compiled code when the OSR entry loop is finished if
          there is no mature profile available for the rest of the method.
graal.DeoptsToDisableOptimisticOptimization = 40                         [Integer]
graal.DetailedAsserts = false                                            [Boolean]
          Enable expensive assertions if normal assertions (i.e. -ea or -esa) are
          enabled.
graal.Dump = null                                                         [String]
          Filter pattern for specifying scopes in which dumping is enabled.
          
          A filter is a list of comma-separated terms of the form:
           
            <pattern>[:<level>]
           
          If <pattern> contains a "*" or "?" character, it is interpreted as a glob pattern.
          Otherwise, it is interpreted as a substring. If <pattern> is empty, it
          matches every scope. If :<level> is omitted, it defaults to 1. The term
          ~<pattern> is a shorthand for <pattern>:0 to disable a debug facility for a pattern.
          
          The default log level is 0 (disabled). Terms with an empty pattern set
          the default log level to the specified value. The last
          matching term with a non-empty pattern selects the level specified. If
          no term matches, the log level is the default level. A filter with no
          terms matches every scope with a log level of 1.
          
          Examples of debug filters:
          --------- 
            (empty string)
          
            Matches any scope with level 1.
          --------- 
            :1
          
            Matches any scope with level 1.
          --------- 
            *
          
            Matches any scope with level 1.
          --------- 
            CodeGen,CodeInstall
          
            Matches scopes containing "CodeGen" or "CodeInstall", both with level 1.
          --------- 
            CodeGen:2,CodeInstall:1
          
            Matches scopes containing "CodeGen" with level 2, or "CodeInstall" with level 1.
          ---------
            Outer:2,Inner:0}
          
            Matches scopes containing "Outer" with log level 2, or "Inner" with log level 0. If the scope
            name contains both patterns then the log level will be 0. This is useful for silencing subscopes.
          ---------
            :1,Dead:2
          
            Matches scopes containing "Dead" with level 2, and all other scopes with level 1.
          --------- 
            Dead:0,:1
          
            Matches all scopes with level 1, except those containing "Dead".   Note that the location of
            the :1 doesn't matter since it's specifying the default log level so it's the same as
            specifying :1,Dead:0.
          --------- 
            Code*
          
            Matches scopes starting with "Code" with level 1.
          --------- 
            Code,~Dead
          
            Matches scopes containing "Code" but not "Dead", with level 1.
graal.DumpOnError = false                                                [Boolean]
          Send compiler IR to dump handlers on error.
graal.DumpOnPhaseChange = null                                            [String]
          Dump a before and after graph if the named phase changes the
          graph.%nThe argument is substring matched against the simple name of
          the phase class
graal.DumpPath = "graal_dumps"                                            [String]
          The directory where various Graal dump files are written.
graal.DumpingErrorsAreFatal = false                                      [Boolean]
          Treat any exceptions during dumping as fatal.
graal.DynamicCountersPrintGroupSeparator = true                          [Boolean]
          Use grouping separators for number printing
graal.EagerSnippets = false                                              [Boolean]
          Eagerly construct extra snippet info.
graal.EscapeAnalysisIterations = 2                                       [Integer]
graal.EscapeAnalysisLoopCutoff = 20                                      [Integer]
graal.EscapeAnalyzeOnly = null                                            [String]
graal.ExactFullUnrollMaxNodes = 800                                      [Integer]
graal.ExactPartialUnrollMaxNodes = 200                                   [Integer]
graal.ExitVMOnException = false                                          [Boolean]
          Alias for CompilationFailureAction=ExitVM.
graal.FailedLoopExplosionIsFatal = false                                 [Boolean]
          Do not bail out but throw an exception on failed loop explosion.
graal.FullUnroll = true                                                  [Boolean]
graal.FullUnrollConstantCompareBoost = 15                                [Integer]
graal.FullUnrollMaxIterations = 600                                      [Integer]
graal.FullUnrollMaxNodes = 400                                           [Integer]
graal.GCDebugStartCycle = -1                                             [Integer]
          Start tracing compiled GC barriers after N garbage collections
          (disabled if N <= 0).
graal.GenLoopSafepoints = true                                           [Boolean]
graal.GenSafepoints = true                                               [Boolean]
graal.GeneratePIC = false                                                [Boolean]
          Generate position independent code
graal.GenericDynamicCounters = false                                     [Boolean]
          Turn on the benchmark counters, and displays the results on VM shutdown
graal.GraalArithmeticStubs = true                                        [Boolean]
          Use Graal arithmetic stubs instead of HotSpot stubs where possible
graal.GraalCompileOnly = null                                             [String]
          A filter applied to a method the VM has selected for compilation by
          Graal. A method not matching the filter is redirected to a lower tier
          compiler. The filter format is the same as for the MethodFilter option.
graal.GraphCompressionThreshold = 70                                     [Integer]
          Graal graph compression is performed when percent of live nodes falls
          below this value
graal.GuardPriorities = true                                             [Boolean]
graal.HideSubstitutionStates = false                                     [Boolean]
          When creating info points hide the methods of the substitutions.
graal.HotSpotDeoptExplicitExceptions = false                             [Boolean]
          Testing only option that forces deopts for exception throws
graal.HotSpotPostOnExceptions = false                                    [Boolean]
          Testing only option that forces deopts for exception throws
graal.HotSpotPrintInlining = false                                       [Boolean]
          Print inlining optimizations
graal.ImmutableCode = false                                              [Boolean]
          Try to avoid emitting code where patching is required
graal.Inline = true                                                      [Boolean]
          Enable inlining
graal.InlineDuringParsing = true                                         [Boolean]
          Inlines trivial methods during bytecode parsing.
graal.InlineDuringParsingMaxDepth = 10                                   [Integer]
          Maximum depth when inlining during bytecode parsing.
graal.InlineEverything = false                                           [Boolean]
graal.InlineIntrinsicsDuringParsing = true                               [Boolean]
          Inlines intrinsic methods during bytecode parsing.
graal.InlineMegamorphicCalls = true                                      [Boolean]
          Inline calls with megamorphic type profile (i.e., not all types could
          be recorded).
graal.InlineMonomorphicCalls = true                                      [Boolean]
          Inline calls with monomorphic type profile.
graal.InlinePartialIntrinsicExitDuringParsing = true                     [Boolean]
          Inlines partial intrinsic exits during bytecode parsing when possible.
          A partial intrinsic exit is a call within an intrinsic to the method
          being intrinsified and denotes semantics of the original method that
          the intrinsic does not support.
graal.InlinePolymorphicCalls = true                                      [Boolean]
          Inline calls with polymorphic type profile.
graal.InlineVTableStubs = true                                           [Boolean]
graal.InliningDepthError = 1000                                          [Integer]
          Maximum inlining depth during partial evaluation before reporting an
          infinite recursion
graal.InterceptBailout = false                                           [Boolean]
          Intercept also bailout exceptions
graal.Intrinsify = true                                                  [Boolean]
          Use compiler intrinsifications.
graal.LIRDynMoveProfileMethod = false                                    [Boolean]
          Enable dynamic move profiling per method.
graal.LIROptConstantLoadOptimization = true                              [Boolean]
          Enable constant load optimization.
graal.LIROptControlFlowOptimizer = true                                  [Boolean]
graal.LIROptEdgeMoveOptimizer = true                                     [Boolean]
graal.LIROptLSRAEliminateSpillMoves = true                               [Boolean]
          Enable spill move elimination.
graal.LIROptLSRAOptimizeSpillPosition = true                             [Boolean]
          Enable spill position optimization
graal.LIROptLSStackSlotAllocator = true                                  [Boolean]
          Use linear scan stack slot allocation.
graal.LIROptNullCheckOptimizer = true                                    [Boolean]
graal.LIROptRedundantMoveElimination = true                              [Boolean]
graal.LIROptStackMoveOptimizer = true                                    [Boolean]
graal.LIROptimization = true                                             [Boolean]
          Enable LIR level optimiztations.
graal.LIRProfileMethods = false                                          [Boolean]
          Enables profiling of methods.
graal.LIRProfileMoves = false                                            [Boolean]
          Enables profiling of move types on LIR level. Move types are for
          example stores (register to stack), constant loads (constant to
          register) or copies (register to register).
graal.LSRAOptSplitOnly = false                                           [Boolean]
          LSRA optimization: Only split but do not reassign
graal.LSRAOptimization = false                                           [Boolean]
          Enable LSRA optimization
graal.LateMembars = true                                                 [Boolean]
          Do not include membars for volatile accesses until the end of
          optimizations.
graal.LimitInlinedInvokes = 5.0                                           [Double]
graal.ListMetrics = false                                                [Boolean]
          Lists on the console at VM shutdown the metric names available to the
          Timers, Counters and MemUseTrackers options. Note that this only lists
          the metrics that were initialized during the VM execution and so will
          not include metrics for compiler code that is not executed.
graal.LoadExceptionObjectInVM = false                                    [Boolean]
          Use a VM runtime call to load and clear the exception object from the
          thread at the start of a compiled exception handler.
graal.Log = null                                                          [String]
          Pattern for specifying scopes in which logging is enabled. See the Dump
          option for the pattern syntax.
graal.LogFile = null                                                      [String]
          File to which logging is sent. A %p in the name will be replaced with a
          string identifying the process, usually the process id and %t will be
          replaced by System.currentTimeMillis(). Using %o as filename sends
          logging to System.out whereas %e sends logging to System.err.
graal.LogVerbose = false                                                 [Boolean]
          Enable more verbose log output when available
graal.LoopHeaderAlignment = 16                                           [Integer]
          Alignment in bytes for loop header blocks.
graal.LoopMaxUnswitch = 3                                                [Integer]
graal.LoopPeeling = true                                                 [Boolean]
graal.LoopUnswitch = true                                                [Boolean]
graal.LoopUnswitchFrequencyBoost = 10.0                                   [Double]
graal.LoopUnswitchMaxIncrease = 500                                      [Integer]
graal.LoopUnswitchTrivial = 10                                           [Integer]
graal.MatchExpressions = true                                            [Boolean]
          Allow backend to match complex expressions.
graal.MaxCompilationProblemsPerAction = 2                                [Integer]
          The maximum number of compilation failures to handle with the action
          specified by CompilationFailureAction before changing to a less verbose
          action. This does not apply to the ExitVM action.
graal.MaxTemplatesPerSnippet = 50                                        [Integer]
graal.MaximumDesiredSize = 20000                                         [Integer]
          Maximum desired size of the compiler graph in nodes.
graal.MaximumEscapeAnalysisArrayLength = 128                             [Integer]
          The maximum length of an array that will be escape analyzed.
graal.MaximumInliningSize = 300                                          [Integer]
          Inlining is explored up to this number of nodes in the graph for each
          call site.
graal.MaximumLoopExplosionCount = 10000                                  [Integer]
          Max number of loop explosions per method.
graal.MaximumRecursiveInlining = 5                                       [Integer]
          Maximum level of recursive inlining.
graal.MegamorphicInliningMinMethodProbability = 0.33                      [Double]
          Minimum probability for methods to be inlined for megamorphic type
          profiles.
graal.MemUseTrackers = null                                               [String]
          Comma separated names of memory usage trackers that are enabled
          irrespective of the value for TrackMemUse option. An empty value
          enables all memory usage trackers unconditionally.
graal.MethodFilter = null                                                 [String]
          Pattern for filtering debug scope output based on method context.
          The syntax for a pattern is:
          
            SourcePatterns = SourcePattern ["," SourcePatterns] .
            SourcePattern = [ Class "." ] method [ "(" [ Parameter { ";" Parameter } ] ")" ] .
            Parameter = Class | "int" | "long" | "float" | "double" | "short" | "char" | "boolean" .
            Class = { package "." } class .
           
          Glob pattern matching (*, ?) is allowed in all parts of the source pattern.
          
          Examples of method filters:
          --------- 
            visit(Argument;BlockScope)  
            
            Matches all methods named "visit", with the first parameter of
            type "Argument", and the second parameter of type "BlockScope".
            The packages of the parameter types are irrelevant.
          ---------
            arraycopy(Object;;;;)
           
            Matches all methods named "arraycopy", with the first parameter
            of type "Object", and four more parameters of any type. The
            packages of the parameter types are irrelevant.
          ---------    
            org.graalvm.compiler.core.graph.PostOrderNodeIterator.*
           
            Matches all methods in the class "org.graalvm.compiler.core.graph.PostOrderNodeIterator".
          ---------    
            *
           
            Matches all methods in all classes
          ---------
            org.graalvm.compiler.core.graph.*.visit
           
            Matches all methods named "visit" in classes in the package
            "org.graalvm.compiler.core.graph".
          ---------
            arraycopy,toString
           
            Matches all methods named "arraycopy" or "toString", meaning that ',' acts as an or operator.
graal.MethodFilterRootOnly = false                                       [Boolean]
          Only check MethodFilter against the root method in the context if true,
          otherwise check all methods
graal.MethodInlineBailoutLimit = 5000                                    [Integer]
          Per-compilation method inlining exploration limit before giving up (use
          0 to disable)
graal.MetricsFile = null                                                  [String]
          File to which metrics are dumped per compilation.
          A CSV format is used if the file ends with .csv otherwise a more
          human readable format is used. The fields in the CSV format are:
                     compilable - method being compiled
            compilable_identity - identity hash code of compilable
                 compilation_nr - where this compilation lies in the ordered
                                  sequence of all compilations identified by
                                  compilable_identity
                 compilation_id - runtime issued identifier for the compilation
                    metric_name - name of metric
                   metric_value - value of metric
graal.MetricsThreadFilter = null                                          [String]
          Only report metrics for threads whose name matches the regular
          expression.
graal.MinimalBulkZeroingSize = 2048                                      [Integer]
          If applicable, use bulk zeroing instructions when the zeroing size in
          bytes exceeds this threshold.
graal.MinimumPeelFrequency = 0.35                                          [Float]
graal.MitigateSpeculativeExecutionAttacks = None                          [String]
          Select a strategy to mitigate speculative execution attacks (e.g.,
          SPECTRE).
          The accepted values are:
                            None - No mitigations are used in JIT compiled code.
                      AllTargets - All branches are protected against speculative attacks.
                                   This has a significant performance impact.
                    GuardTargets - Only branches that preserve Java memory safety are protected.
                                   This has less performance impact than AllTargets.
            NonDeoptGuardTargets - GuardTargets except that branches which deoptimize are not
                                   protected since they can not be executed repeatedly.
graal.NDCV = 0                                                           [Integer]
          Run level for NoDeadCodeVerifyHandler (0 = off, 1 = info, 2 = verbose,
          3 = fatal)
graal.NodeCounters = false                                               [Boolean]
          Counts the number of instances of each node class.
graal.NonFatalIdenticalCompilationSnapshots = 20                         [Integer]
          Number of contiguous identical compiler thread stack traces allowed
          before the VM exits on the basis of a stuck compilation.
graal.OmitHotExceptionStacktrace = false                                 [Boolean]
graal.OptAssumptions = true                                              [Boolean]
graal.OptConvertDeoptsToGuards = true                                    [Boolean]
graal.OptDeoptimizationGrouping = true                                   [Boolean]
graal.OptDevirtualizeInvokesOptimistically = true                        [Boolean]
graal.OptEarlyReadElimination = true                                     [Boolean]
graal.OptEliminateGuards = true                                          [Boolean]
graal.OptEliminatePartiallyRedundantGuards = true                        [Boolean]
graal.OptFilterProfiledTypes = true                                      [Boolean]
graal.OptFloatingReads = true                                            [Boolean]
graal.OptImplicitNullChecks = true                                       [Boolean]
graal.OptReadElimination = true                                          [Boolean]
graal.OptScheduleOutOfLoops = true                                       [Boolean]
graal.PEAInliningHints = false                                           [Boolean]
graal.PartialEscapeAnalysis = true                                       [Boolean]
graal.PartialUnroll = true                                               [Boolean]
graal.PeelALot = false                                                   [Boolean]
graal.PrintBackendCFG = true                                             [Boolean]
          Enable dumping LIR, register allocation and code generation info to the
          C1Visualizer.
graal.PrintCFG = false                                                   [Boolean]
          Enable dumping to the C1Visualizer. Enabling this option implies
          PrintBackendCFG.
graal.PrintCanonicalGraphStringFlavor = 0                                [Integer]
          Choose format used when dumping canonical text for graphs: 0 gives a
          scheduled graph (better for spotting changes involving the schedule)
          while 1 gives a CFG containing expressions rooted at fixed nodes
          (better for spotting small structure differences)
graal.PrintCanonicalGraphStrings = false                                 [Boolean]
          Enable dumping canonical text from for graphs.
graal.PrintCompilation = false                                           [Boolean]
          Print an informational line to the console for each completed
          compilation.
graal.PrintGraph = File                                                   [String]
          Where IdealGraphVisualizer graph dumps triggered by Dump or DumpOnError
          should be written.
          The accepted values are:
                File - Dump IGV graphs to the local file system (see DumpPath).
             Network - Dump IGV graphs to the network destination specified by PrintGraphHost and PrintGraphPort.
                       If a network connection cannot be opened, dumping falls back to file dumping. 
             Disable - Do not dump IGV graphs.
graal.PrintGraphFile = true                                              [Boolean]
          Setting to true sets PrintGraph=file, setting to false sets
          PrintGraph=network
graal.PrintGraphHost = "127.0.0.1"                                        [String]
          Host part of the address to which graphs are dumped.
graal.PrintGraphPort = 4445                                              [Integer]
          Port part of the address to which graphs are dumped in binary format.
graal.PrintGraphWithSchedule = false                                     [Boolean]
          Schedule graphs as they are dumped.
graal.PrintIRWithLIR = false                                             [Boolean]
          Print HIR along side LIR as the latter is generated
graal.PrintLIRWithAssembly = false                                       [Boolean]
          Include the LIR as comments with the final assembly.
graal.PrintProfilingInformation = false                                  [Boolean]
          Print profiling information when parsing a method's bytecode
graal.PrintTruffleTrees = true                                           [Boolean]
          Enable dumping Truffle ASTs to the IdealGraphVisualizer.
graal.ProbabilisticProfiling = true                                      [Boolean]
          Control probabilistic profiling on AMD64
graal.ProfileAllocations = false                                         [Boolean]
          Enable profiling of allocation sites.
graal.ProfileAllocationsContext = AllocatingMethod                        [String]
          Control the naming and granularity of the counters when using
          ProfileAllocations.
          The accepted values are:
                  AllocatingMethod - a counter per method
                   InstanceOrArray - one counter for all instance allocations and
                                     one counter for all array allocations 
                     AllocatedType - one counter per allocated type
            AllocatedTypesInMethod - one counter per allocated type, per method
           
graal.ProfileBackedges = true                                            [Boolean]
          Emit profiling of backedges
graal.ProfileCompiledMethods = false                                     [Boolean]
graal.ProfileInvokes = true                                              [Boolean]
          Emit profiling of invokes
graal.ProfileMonitors = false                                            [Boolean]
          Enable profiling of monitor operations.
graal.ProfileSimpleMethods = true                                        [Boolean]
          Profile simple methods
graal.RawConditionalElimination = true                                   [Boolean]
graal.ReadEliminationMaxLoopVisits = 5                                   [Integer]
graal.ReassociateInvariants = true                                       [Boolean]
graal.ReduceDCE = true                                                   [Boolean]
          Disable optional dead code eliminations
graal.RegisterPressure = null                                             [String]
          Comma separated list of registers that register allocation is limited
          to.
graal.RemoveNeverExecutedCode = true                                     [Boolean]
graal.ReplaceInputsWithConstantsBasedOnStamps = true                     [Boolean]
graal.ShowConfiguration = none                                            [String]
          Writes to the VM log information about the compiler configuration
          selected.
graal.ShowDumpFiles = false                                              [Boolean]
          Print the name of each dump file path as it's created.
graal.ShowSubstitutionSourceInfo = false                                 [Boolean]
          Controls whether the source position information of snippets and method
          substitutions are exposed to HotSpot. Can be useful when profiling to
          get more precise position information.
graal.SimpleFastInflatedLocking = true                                   [Boolean]
          Handle simple cases for inflated monitors in the fast-path.
graal.SimpleMethodCalls = 1                                              [Integer]
          Maximum number of calls in a simple method
graal.SimpleMethodGraphSize = 256                                        [Integer]
          Maximum number of nodes in a graph for a simple method
graal.SimpleMethodIndirectCalls = 0                                      [Integer]
          Maximum number of indirect calls in a simple moethod
graal.SmallCompiledLowLevelGraphSize = 330                               [Integer]
          If the previous low-level graph size of the method exceeds the
          threshold, it is not inlined.
graal.SnippetCounters = false                                            [Boolean]
          Enable counters for various paths in snippets.
graal.StressExplicitExceptionCode = false                                [Boolean]
          Stress the code emitting explicit exception throwing code.
graal.StressInvokeWithExceptionNode = false                              [Boolean]
          Stress the code emitting invokes with explicit exception edges.
graal.StressTestEarlyReads = false                                       [Boolean]
          Stress the code by emitting reads at earliest instead of latest point.
graal.SupportJsrBytecodes = true                                         [Boolean]
graal.SupportOSRWithLocks = true                                         [Boolean]
          Support OSR compilations with locks. If DeoptAfterOSR is true we can
          per definition not have unbalanced enter/exits mappings. If
          DeoptAfterOSR is false insert artificial monitor enters after the
          OSRStart to have balanced enter/exits in the graph.
graal.TailDuplicationProbability = 0.5                                    [Double]
graal.TailDuplicationTrivialSize = 1                                     [Integer]
graal.TierABackedgeNotifyFreqLog = 16                                    [Integer]
          Backedge notification frequency
graal.TierABackedgeProfileProbabilityLog = 12                            [Integer]
          Backedge profile probability
graal.TierAInvokeInlineeNotifyFreqLog = -1                               [Integer]
          Inlinee invocation notification frequency (-1 means count, but do not
          notify)
graal.TierAInvokeNotifyFreqLog = 13                                      [Integer]
          Invocation notification frequency
graal.TierAInvokeProfileProbabilityLog = 8                               [Integer]
          Invocation profile probability
graal.TieredAOT = false                                                  [Boolean]
          Do profiling and callbacks to tiered runtime
graal.Time = null                                                         [String]
          Pattern for specifying scopes in which timing is enabled. See the Dump
          option for the pattern syntax. An empty value enables all timers
          unconditionally.
graal.TimedDynamicCounters = -1                                          [Integer]
          Turn on the benchmark counters, and displays the results every n
          milliseconds
graal.Timers = null                                                       [String]
          Comma separated names of timers that are enabled irrespective of the
          value for Time option. An empty value enables all timers
          unconditionally.
graal.TraceBytecodeParserLevel = 0                                       [Integer]
          The trace level for the bytecode parser. A value of 1 enables
          instruction tracing and any greater value emits a frame state trace
          just prior to each instruction trace.Instruction tracing output from
          multiple compiler threads will be interleaved so use of this option
          make most sense for single threaded compilation. The MethodFilter
          option can be used to refine tracing to selected methods.
graal.TraceEscapeAnalysis = false                                        [Boolean]
graal.TraceExceptionHandlerStub = false                                  [Boolean]
          Trace execution of stub used to handle an exception thrown by a callee.
graal.TraceInlineDuringParsing = false                                   [Boolean]
          Traces inlining performed during bytecode parsing.
graal.TraceInlining = false                                              [Boolean]
          Enable tracing of inlining decisions.
          Output format:
            compilation of 'Signature of the compilation root method':
              at 'Signature of the root method' ['Bytecode index']: <'Phase'> 'Child method signature': 'Decision made about this callsite'
                at 'Signature of the child method' ['Bytecode index']: 
                   |--<'Phase 1'> 'Grandchild method signature': 'First decision made about this callsite'
                   \--<'Phase 2'> 'Grandchild method signature': 'Second decision made about this callsite'
                at 'Signature of the child method' ['Bytecode index']: <'Phase'> 'Another grandchild method signature': 'The only decision made about this callsite.'
graal.TraceInliningForStubsAndSnippets = false                           [Boolean]
          Enable inlining decision tracing in stubs and snippets.
graal.TraceLIRGeneratorLevel = 0                                         [Integer]
          The trace level for the LIR generator
graal.TraceMonitorsMethodFilter = null                                    [String]
          Trace monitor operations in methods whose fully qualified name contains
          this substring.
graal.TraceMonitorsTypeFilter = null                                      [String]
          Trace monitor operations on objects whose type contains this substring.
graal.TraceParserPlugins = false                                         [Boolean]
          Traces use of plugins during bytecode parsing.
graal.TraceUnwindStub = false                                            [Boolean]
          Trace execution of the stub that routes an exception to a handler in
          the calling frame.
graal.TrackMemUse = null                                                  [String]
          Pattern for specifying scopes in which memory use tracking is enabled.
          See the Dump option for the pattern syntax. An empty value enables all
          memory use trackers unconditionally.
graal.TrackNodeInsertion = false                                         [Boolean]
          Track source stack trace where a node was inserted into the graph.
graal.TrackNodeSourcePosition = false                                    [Boolean]
          Track the NodeSourcePosition.
graal.TrivialInliningSize = 10                                           [Integer]
          Graphs with less than this number of nodes are trivial and therefore
          always inlined.
graal.TrustFinalDefaultFields = true                                     [Boolean]
          Determines whether to treat final fields with default values as
          constant.
graal.TypeCheckMaxHints = 2                                              [Integer]
          The maximum number of profiled types that will be used when compiling a
          profiled type check. Note that TypeCheckMinProfileHitProbability also
          influences whether profiling info is used in compiled type checks.
graal.TypeCheckMinProfileHitProbability = 0.5                             [Double]
          If the probability that a type check will hit one the profiled types
          (up to TypeCheckMaxHints) is below this value, the type check will be
          compiled without profiling info
graal.UnrollMaxIterations = 16                                           [Integer]
graal.UseCompilationStatistics = false                                   [Boolean]
          Enables CompilationStatistics.
graal.UseEncodedGraphs = false                                           [Boolean]
          Encode and decode snippets and substitutions before parsing to test
          libgraal code path. This option is ignored in the context of libgraal.
graal.UseExceptionProbability = true                                     [Boolean]
graal.UseGraalStubs = true                                               [Boolean]
          Use Graal-generated stubs for complicated LIR operations instead of
          embedding all the emitted code.
graal.UseIndexMasking = false                                            [Boolean]
          Use index masking after bounds check to mitigate speculative execution
          attacks.
graal.UseLoopLimitChecks = true                                          [Boolean]
graal.UseSnippetGraphCache = true                                        [Boolean]
          Use a cache for snippet graphs.
graal.UseSnippetTemplateCache = true                                     [Boolean]
          Use a LRU cache for snippet templates.
graal.UseTrappingNullChecks = true                                       [Boolean]
          Use traps for null checks instead of explicit null-checks
graal.UseTypeCheckHints = true                                           [Boolean]
graal.Verify = null                                                       [String]
          Pattern for specifying scopes in which logging is enabled. See the Dump
          option for the pattern syntax.
graal.VerifyBalancedMonitors = false                                     [Boolean]
          Emit extra code to dynamically check monitor operations are balanced.
graal.VerifyGraalGraphEdges = false                                      [Boolean]
          Perform expensive verification of graph inputs, usages, successors and
          predecessors
graal.VerifyGraalGraphs = true                                           [Boolean]
          Verify graphs often during compilation when assertions are turned on
graal.VerifyGraalPhasesSize = false                                      [Boolean]
          Verify before - after relation of the relative, computed, code size of
          a graph
graal.VerifyHeapAtReturn = false                                         [Boolean]
          Perform platform dependent validation of the Java heap at returns
graal.VerifyKillCFGUnusedNodes = false                                   [Boolean]
          Verify that there are no new unused nodes when performing killCFG
graal.VerifyPhases = false                                               [Boolean]
graal.ZapStackOnMethodEntry = false                                      [Boolean]
</pre>

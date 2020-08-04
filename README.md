# Scalability.ini
[/Script/Engine.GameUserSettings] 
bUseDesiredScreenHeight=False  

[ScalabilitySettings] 
PerfIndexValues_ResolutionQuality="50 50 50 50" 

[ScalabilityGroups] 
sg.ResolutionQuality=95 
sg.ViewDistanceQuality=4 
sg.AntiAliasingQuality=3 
sg.ShadowQuality=0 
sg.PostProcessQuality=1 
sg.TextureQuality=1 
sg.EffectsQuality=1 
sg.FoliageQuality=1 
sg.TrueSkyQuality=0 
sg.GroundClutterQuality=0 
sg.IBLQuality=0 
sg.PUBGQualityLv1=1 
sg.HeightFieldShadowQuality=0 
sg.FrameRate=60fps 
sg.FrameRateLock=60fps
sg.FrameRateLimit=1000.000000fps 
sg.AnisotropicFiltering=TextureFiltering  

[FoliageQuality] 
r.ParticleLightQuality=1 
foliage.LODDistanceScale=0.8 
foliage.DensityScale=0.75 
grass.DensityScale=0.75 
foliage.MinLOD=0  

[AntiAliasingQuality] 
r.MSAA.CompositingSampleCount=1 
r.PostProcessAAQuality=3  

[ViewDistanceQuality] 
r.SkeletalMeshLODBias=0 
r.ViewDistanceScale=0.8
r.StaticMeshLODDistanceScale=1.3  

[ShadowQuality] 
r.LightFunctionQuality=1 
r.ShadowQuality=0 
r.Shadow.CSM.MaxCascades=0 
r.Shadow.MaxResolution=1024 
r.Shadow.MaxCSMResolution=2048 
r.Shadow.RadiusThreshold=0.04 
r.Shadow.DistanceScale=0.85 
r.Shadow.CSM.TransitionScale=0.8 
r.Shadow.PreShadowResolutionFactor=0.5 
r.DistanceFieldShadowing=0 
r.DistanceFieldAO=0 
r.VolumetricFog=0 
r.VolumetricFog.GridPixelSize=16
r.VolumetricFog.GridSizeZ=64 
r.VolumetricFog.HistoryMissSupersampleCount=4 
r.LightMaxDrawDistanceScale=1 
r.CapsuleShadows=1  

[PostProcessQuality] 
r.PostProcessQuality=1 
r.DepthOfFieldQuality=0 
r.RenderTargetPoolMin=200 
r.Upscale.Quality=2 
r.MotionBlurQuality=3 
r.AmbientOcclusionMipLevelFactor=0.6 
r.AmbientOcclusionMaxQuality=100
r.AmbientOcclusionLevels=-1 
r.AmbientOcclusionRadiusScale=1.5 
r.LensFlareQuality=2 
r.SceneColorFringeQuality=1 
r.EyeAdaptationQuality=2 
r.BloomQuality=0 
r.FastBlurThreshold=3 
r.Tonemapper.GrainQuantization=1 
r.LightShaftQuality=1 
r.Tonemapper.Quality=0 
r.Filter.SizeScale=0.8 
r.Tonemapper.Quality=5  

[TextureQuality] 
r.Streaming.MipBias=0 
r.MaxAnisotropy=0 
r.DefaultFeature.AntiAliasing=3 
r.SceneColorFormat=0 
r.Mobile.SceneColorFormat=0 
r.Streaming.LimitPoolSizeToVRAM=0 
r.Streaming.PoolSize=400 
r.Streaming.MaxEffectiveScreenSize=1  

[TextureStreaming] 
BoostPlayerTextures=1.0 
AllowStreamingLightmaps=true 
PoolSize=340 
MemoryMargin=20 
MemoryLoss=0 
HysteresisLimit=20 
DropMipLevelsLimit=20 
StopIncreasingLimit=12 
StopStreamingLimit=8 
MinEvictSize=10
MinFudgeFactor=0.5 
FudgeFactorDecreaseRateOfChange=-1 
FudgeFactorIncreaseRateOfChange=0.5 
MinRequestedMipsToConsider=11 
MinTimeToGuaranteeMinMipCount=0
MaxTimeToGuaranteeMinMipCount=0
 UsePriorityStreaming=true
 bAllowSwitchingStreaming=true 
UseDynamicStreaming=true 
bEnableAsyncReallocation=false
 bEnableAsyncDefrag=talse 
UseTextureFileCache=false
 LoadMapTimeLimit=4.0 
LightmapStreamingFactor=0.05 
ShadowmapStreamingFactor=0.05
 MaxLightmapRadius=4250.0
 TextureFileCacheBulkDataAlignment=1

 [EffectsQuality] 
r.TranslucencyLightingVolumeDim=1 
r.RefractionQuality=0
r.DefaultFeature.AntiAliasing=3 
r.AntiAliasingQuality=3
r.SceneColorFormat=0 
r.Mobile.SceneColorFormat=0 
r.UserHDRSetting=4
 r.ScreenPercentage=64 
r.SSR.Quality=0
 r.DetailMode=0 r.TranslucencyVolumeBlur=1 r.MaterialQualityLevel=0 r.SSS.Scale=0 r.SSS.SampleSet=0 r.SSS.Quality=0 r.SSS.HalfRes=0 r.EmitterSpawnRateScale=0.75 r.ParticleLightQuality=1

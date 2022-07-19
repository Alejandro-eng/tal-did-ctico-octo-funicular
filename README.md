# tal-did-ctico-octo-funicular
Crash with the mod Oh the biomes you'll go
CRASH REPORT:


---- Minecraft Crash Report ----
// I let you down. Sorry :(

Time: 19/7/22 10:49
Description: Mod loading error has occurred

java.lang.Exception: Mod Loading has failed
	at net.minecraftforge.logging.CrashReportExtender.dumpModLoadingCrashReport(CrashReportExtender.java:55) ~[forge-1.18.2-40.0.40-universal.jar%2358!/:?] {re:classloading}
	at net.minecraftforge.client.loading.ClientModLoader.completeModLoading(ClientModLoader.java:169) ~[forge-1.18.2-40.0.40-universal.jar%2358!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.lambda$new$1(Minecraft.java:555) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:byg_forge.mixins.json:client.MixinMinecraft,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.Util.m_137521_(Util.java:397) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.lambda$new$2(Minecraft.java:549) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:byg_forge.mixins.json:client.MixinMinecraft,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.LoadingOverlay.m_6305_(LoadingOverlay.java:135) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:877) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1044) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:byg_forge.mixins.json:client.MixinMinecraft,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:663) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:byg_forge.mixins.json:client.MixinMinecraft,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:205) ~[client-1.18.2-20220404.173914-srg.jar%2354!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:45) ~[fmlloader-1.18.2-40.0.40.jar%2316!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:149) [bootstraplauncher-1.0.0.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at potionstudios.byg.reg.forge.ForgeRegistrationFactory$Provider$1.asHolder(ForgeRegistrationFactory.java:101) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
-- MOD byg --
Details:
	Caused by 0: java.lang.reflect.InvocationTargetException
		at jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method) ~[?:?] {}
		at jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:77) ~[?:?] {}
		at jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45) ~[?:?] {}
		at java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:499) ~[?:?] {}
		at java.lang.reflect.Constructor.newInstance(Constructor.java:480) ~[?:?] {}
		at net.minecraftforge.fml.javafmlmod.FMLModContainer.constructMod(FMLModContainer.java:81) ~[javafmllanguage-1.18.2-40.0.40.jar%2356!/:?] {}
		at net.minecraftforge.fml.ModContainer.lambda$buildTransitionHandler$4(ModContainer.java:120) ~[fmlcore-1.18.2-40.0.40.jar%2355!/:?] {}
		at java.util.concurrent.CompletableFuture$AsyncRun.run(CompletableFuture.java:1804) ~[?:?] {}
		at java.util.concurrent.CompletableFuture$AsyncRun.exec(CompletableFuture.java:1796) ~[?:?] {}
		at java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373) ~[?:?] {}
		at java.util.concurrent.ForkJoinPool$WorkQueue.topLevelExec(ForkJoinPool.java:1182) ~[?:?] {}
		at java.util.concurrent.ForkJoinPool.scan(ForkJoinPool.java:1655) ~[?:?] {}
		at java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1622) ~[?:?] {}
		at java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165) ~[?:?] {}

	Mod File: Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar
	Failure message: Oh The Biomes You'll Go (byg) has failed to load correctly
		java.lang.reflect.InvocationTargetException: null
	Mod Version: 1.4
	Mod Issue URL: https://github.com/AOCAWOL/BYG/issues
	Exception message: java.lang.NoSuchMethodError: 'java.util.Optional net.minecraftforge.registries.RegistryObject.getHolder()'
Stacktrace:
	at potionstudios.byg.reg.forge.ForgeRegistrationFactory$Provider$1.asHolder(ForgeRegistrationFactory.java:101) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
	at potionstudios.byg.common.world.structure.BYGStructureSets.register(BYGStructureSets.java:23) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
	at potionstudios.byg.common.world.structure.BYGStructureSets.<clinit>(BYGStructureSets.java:18) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
	at potionstudios.byg.common.world.biome.BYGBiomes.loadClass(BYGBiomes.java:130) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
	at potionstudios.byg.core.BYGRegistry.loadClasses(BYGRegistry.java:42) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
	at potionstudios.byg.BYGForge.<init>(BYGForge.java:70) ~[Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar%2352!/:1.4-RC-24] {re:classloading}
	at jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45) ~[?:?] {}
	at java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:499) ~[?:?] {}
	at java.lang.reflect.Constructor.newInstance(Constructor.java:480) ~[?:?] {}
	at net.minecraftforge.fml.javafmlmod.FMLModContainer.constructMod(FMLModContainer.java:81) ~[javafmllanguage-1.18.2-40.0.40.jar%2356!/:?] {}
	at net.minecraftforge.fml.ModContainer.lambda$buildTransitionHandler$4(ModContainer.java:120) ~[fmlcore-1.18.2-40.0.40.jar%2355!/:?] {}
	at java.util.concurrent.CompletableFuture$AsyncRun.run(CompletableFuture.java:1804) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$AsyncRun.exec(CompletableFuture.java:1796) ~[?:?] {}
	at java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373) ~[?:?] {}
	at java.util.concurrent.ForkJoinPool$WorkQueue.topLevelExec(ForkJoinPool.java:1182) ~[?:?] {}
	at java.util.concurrent.ForkJoinPool.scan(ForkJoinPool.java:1655) ~[?:?] {}
	at java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1622) ~[?:?] {}
	at java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165) ~[?:?] {}


-- System Details --
Details:
	Minecraft Version: 1.18.2
	Minecraft Version ID: 1.18.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.1, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 4013401624 bytes (3827 MiB) / 4932501504 bytes (4704 MiB) up to 10737418240 bytes (10240 MiB)
	CPUs: 12
	Processor Vendor: AuthenticAMD
	Processor Name: AMD Ryzen 5 3600 6-Core Processor              
	Identifier: AuthenticAMD Family 23 Model 113 Stepping 0
	Microarchitecture: Zen 2
	Frequency (GHz): 3,60
	Number of physical packages: 1
	Number of physical CPUs: 6
	Number of logical CPUs: 12
	Graphics card #0 name: NVIDIA GeForce GTX 1660 SUPER
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095,00
	Graphics card #0 deviceId: 0x21c4
	Graphics card #0 versionInfo: DriverVersion=31.0.15.1640
	Memory slot #0 capacity (MB): 8192,00
	Memory slot #0 clockSpeed (GHz): 2,13
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 8192,00
	Memory slot #1 clockSpeed (GHz): 2,13
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 18765,35
	Virtual memory used (MB): 12736,50
	Swap memory total (MB): 2432,00
	Swap memory used (MB): 169,60
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx10G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	ModLauncher: 9.1.3+9.1.3+main.9b69c82a
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		 mixin PLUGINSERVICE 
		 eventbus PLUGINSERVICE 
		 slf4jfixer PLUGINSERVICE 
		 object_holder_definalize PLUGINSERVICE 
		 runtime_enum_extender PLUGINSERVICE 
		 capability_token_subclass PLUGINSERVICE 
		 accesstransformer PLUGINSERVICE 
		 runtimedistcleaner PLUGINSERVICE 
		 mixin TRANSFORMATIONSERVICE 
		 fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		javafml@null
	Mod List: 
		client-1.18.2-20220404.173914-srg.jar             |Minecraft                     |minecraft                     |1.18.2              |COMMON_SET|Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		Oh_The_Biomes_You'll_Go-forge-1.18.2-1.4-RC-24.jar|Oh The Biomes You'll Go       |byg                           |1.4                 |ERROR     |Manifest: NOSIGNATURE
		TerraBlender-forge-1.18.2-1.1.0.99.jar            |TerraBlender                  |terrablender                  |1.18.2-1.1.0.99     |COMMON_SET|Manifest: NOSIGNATURE
		forge-1.18.2-40.0.40-universal.jar                |Forge                         |forge                         |40.0.40             |COMMON_SET|Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
	Crash Report UUID: 76742cff-b781-4849-98d9-7d1f2682a4b7
	FML: 40.0
	Forge: net.minecraftforge:40.0.40

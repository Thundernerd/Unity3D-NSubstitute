# Changelog

## [v4.2.2](https://github.com/nsubstitute/nsubstitute/tree/v4.2.2) (2020-06-13)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v4.2.1...v4.2.2)

**Fixed bugs:**

- Mocked out parameter value is stuck inspite of calling CallRouter.Clear\(ClearOptions.All\) [\#589](https://github.com/nsubstitute/NSubstitute/issues/589)

**Closed issues:**

- Is there a way to specify receive times for same function with different argument? [\#620](https://github.com/nsubstitute/NSubstitute/issues/620)
- DidNotReceive\(\) and Received\(\) results True if property is sring\[\] [\#618](https://github.com/nsubstitute/NSubstitute/issues/618)
- Substitute.ForPartsOf\(\) usage -- or Alternative? [\#608](https://github.com/nsubstitute/NSubstitute/issues/608)
- Exceptions by NSubstitute affect the next test [\#605](https://github.com/nsubstitute/NSubstitute/issues/605)
- Calling .Returns with the return value of a previously-configured substitute results in default value instead [\#603](https://github.com/nsubstitute/NSubstitute/issues/603)
- Setting returnvalue to a substitute, previously configured in a AutoFixture.Register\(\) call - throws CouldNotSetReturnDueToNoLastCallException [\#602](https://github.com/nsubstitute/NSubstitute/issues/602)
- Intermittent ArgumentNullException thrown in AutoTaskProvider [\#600](https://github.com/nsubstitute/NSubstitute/issues/600)
- Improve project structure \(csproj\) [\#593](https://github.com/nsubstitute/NSubstitute/issues/593)
- An unmocked method leaves its out parameter value untouched [\#590](https://github.com/nsubstitute/NSubstitute/issues/590)
- Can we have an aditonal overload of Received\(\) [\#588](https://github.com/nsubstitute/NSubstitute/issues/588)
- Building on Mac/Linux with net45/net46 targets [\#335](https://github.com/nsubstitute/NSubstitute/issues/335)

**Merged pull requests:**

- Update rake to 13.0.1 [\#611](https://github.com/nsubstitute/NSubstitute/pull/611) ([dtchepak](https://github.com/dtchepak))
- Doc fixes [\#606](https://github.com/nsubstitute/NSubstitute/pull/606) ([dtchepak](https://github.com/dtchepak))
- Fix thread-safety issue in AutoValueProvidersFactory [\#601](https://github.com/nsubstitute/NSubstitute/pull/601) ([zvirja](https://github.com/zvirja))
- Improve organization in csproj files [\#594](https://github.com/nsubstitute/NSubstitute/pull/594) ([joaopgrassi](https://github.com/joaopgrassi))
- Make dotnet build work without having NetFX installed [\#592](https://github.com/nsubstitute/NSubstitute/pull/592) ([joaopgrassi](https://github.com/joaopgrassi))

## [v4.2.1](https://github.com/nsubstitute/nsubstitute/tree/v4.2.1) (2019-07-15)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v4.2.0...v4.2.1)

**Fixed bugs:**

- Assigning out arg can throw when using inheritance [\#577](https://github.com/nsubstitute/NSubstitute/issues/577)

**Closed issues:**

- Nsubstitute mock method with any arguments is not working .net core [\#580](https://github.com/nsubstitute/NSubstitute/issues/580)
- Method Save\(\) not found on Interface Microsoft.Office.Interop.Outlook.AppointmentItem when used in different project [\#575](https://github.com/nsubstitute/NSubstitute/issues/575)
- \[SOLVED\] Checking a specific Received Call when method is called multiple times but with different parameters. [\#574](https://github.com/nsubstitute/NSubstitute/issues/574)
- Raise.Event\(\) is not thread-safe, or is subject to race condition [\#573](https://github.com/nsubstitute/NSubstitute/issues/573)
- Calling InOrder is causing the next test to error out.  [\#572](https://github.com/nsubstitute/NSubstitute/issues/572)
- Received.InOrder invokes "returnThis" callback for substitute methods when it shouldn't\(?\) [\#569](https://github.com/nsubstitute/NSubstitute/issues/569)
- Build doesn't run if working directory is `build` folder [\#568](https://github.com/nsubstitute/NSubstitute/issues/568)
- Remove NuGet binary from repo [\#562](https://github.com/nsubstitute/NSubstitute/issues/562)
- Unable to compile project without manually adding entry with System.Runtime to \*.csproj file [\#501](https://github.com/nsubstitute/NSubstitute/issues/501)
- Investigate moving build to FAKE 5 [\#440](https://github.com/nsubstitute/NSubstitute/issues/440)

**Merged pull requests:**

- Do not invoke configured result in query [\#579](https://github.com/nsubstitute/NSubstitute/pull/579) ([zvirja](https://github.com/zvirja))
- Fix by ref value might be not re-assigned [\#578](https://github.com/nsubstitute/NSubstitute/pull/578) ([zvirja](https://github.com/zvirja))
- Minor tweaking of build script [\#571](https://github.com/nsubstitute/NSubstitute/pull/571) ([zvirja](https://github.com/zvirja))
- Use absolute path for the solution and project files [\#570](https://github.com/nsubstitute/NSubstitute/pull/570) ([alexandrnikitin](https://github.com/alexandrnikitin))
- Update to FAKE 5 [\#490](https://github.com/nsubstitute/NSubstitute/pull/490) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v4.2.0](https://github.com/nsubstitute/nsubstitute/tree/v4.2.0) (2019-05-19)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v4.1.0...v4.2.0)

**Fixed bugs:**

- Error raising Action\<T\> events when T is an array of a reference type [\#560](https://github.com/nsubstitute/NSubstitute/issues/560)

**Closed issues:**

- Received range of calls [\#558](https://github.com/nsubstitute/NSubstitute/issues/558)

**Merged pull requests:**

- Add NSubstitute.Analyzers recommendation to bug report template [\#566](https://github.com/nsubstitute/NSubstitute/pull/566) ([dtchepak](https://github.com/dtchepak))
- Add Quantity.Within\(min, max\) \(\#558\) [\#564](https://github.com/nsubstitute/NSubstitute/pull/564) ([dtchepak](https://github.com/dtchepak))
- Fix event params ambiguity and add thread-safety [\#563](https://github.com/nsubstitute/NSubstitute/pull/563) ([zvirja](https://github.com/zvirja))
- Use `default` keyword when AnyArg is used [\#559](https://github.com/nsubstitute/NSubstitute/pull/559) ([zvirja](https://github.com/zvirja))
- Post 4.1 prep [\#557](https://github.com/nsubstitute/NSubstitute/pull/557) ([dtchepak](https://github.com/dtchepak))

## [v4.1.0](https://github.com/nsubstitute/nsubstitute/tree/v4.1.0) (2019-05-04)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v4.0.0...v4.1.0)

**Fixed bugs:**

- Internal Exception [\#533](https://github.com/nsubstitute/NSubstitute/issues/533)
- ArgumentOutOfRangeException when Arg matcher is used with class nested in generic class  [\#515](https://github.com/nsubstitute/NSubstitute/issues/515)
- It's a library [\#545](https://github.com/nsubstitute/NSubstitute/pull/545) ([dtchepak](https://github.com/dtchepak))

**Closed issues:**

- Received\(\).Property do not return a value mocked by Returns\(\) method [\#548](https://github.com/nsubstitute/NSubstitute/issues/548)
- Where is `any Boolean` coming from. [\#544](https://github.com/nsubstitute/NSubstitute/issues/544)
- How to verify function calls with params keyword [\#539](https://github.com/nsubstitute/NSubstitute/issues/539)
- Using both DateTimeOffset and DateTimeOffset? in an interface gives unexpected error [\#538](https://github.com/nsubstitute/NSubstitute/issues/538)
- Setting out and ref args documentation [\#535](https://github.com/nsubstitute/NSubstitute/issues/535)
- NS2003 triggers a warning when InternalsVisibleTo using strong name [\#522](https://github.com/nsubstitute/NSubstitute/issues/522)
- Mock a void method without out/ref parameters [\#517](https://github.com/nsubstitute/NSubstitute/issues/517)
- Please change the link of the repo to HTTPS and enforce https on nsubstitute.github.io [\#505](https://github.com/nsubstitute/NSubstitute/issues/505)
- Docs: Document reason we don't support non-virtual members [\#502](https://github.com/nsubstitute/NSubstitute/issues/502)
- Upgrade to 4.0 causes event not to work [\#500](https://github.com/nsubstitute/NSubstitute/issues/500)
- Docs: mention limitations of `internal` members [\#498](https://github.com/nsubstitute/NSubstitute/issues/498)
- Migrate from `licenceUrl` to `license` element in nuspec [\#495](https://github.com/nsubstitute/NSubstitute/issues/495)
- Docs: Update website to de-emphasise discussion group [\#485](https://github.com/nsubstitute/NSubstitute/issues/485)
- Search documentation [\#35](https://github.com/nsubstitute/NSubstitute/issues/35)

**Merged pull requests:**

- Remove redundant argument specs cleanup [\#556](https://github.com/nsubstitute/NSubstitute/pull/556) ([zvirja](https://github.com/zvirja))
- Rethrow exception wrapped in task [\#555](https://github.com/nsubstitute/NSubstitute/pull/555) ([zvirja](https://github.com/zvirja))
- Use license expression instead of file [\#554](https://github.com/nsubstitute/NSubstitute/pull/554) ([zvirja](https://github.com/zvirja))
- Add ability to decorate existing registrations [\#553](https://github.com/nsubstitute/NSubstitute/pull/553) ([zvirja](https://github.com/zvirja))
- Rephrase to avoid potential confusion [\#552](https://github.com/nsubstitute/NSubstitute/pull/552) ([zvirja](https://github.com/zvirja))
- Fix Travis CI build [\#550](https://github.com/nsubstitute/NSubstitute/pull/550) ([dtchepak](https://github.com/dtchepak))
- Update arg matcher misuse docs [\#549](https://github.com/nsubstitute/NSubstitute/pull/549) ([dtchepak](https://github.com/dtchepak))
- Eliminate unnecessary allocations and improve performance [\#547](https://github.com/nsubstitute/NSubstitute/pull/547) ([zvirja](https://github.com/zvirja))
- Test auto-subbed Tasks are completed \(\#541\) [\#543](https://github.com/nsubstitute/NSubstitute/pull/543) ([dtchepak](https://github.com/dtchepak))
- Improve return configuration [\#542](https://github.com/nsubstitute/NSubstitute/pull/542) ([zvirja](https://github.com/zvirja))
- Doc updates [\#540](https://github.com/nsubstitute/NSubstitute/pull/540) ([dtchepak](https://github.com/dtchepak))
- Use Castle to generate delegate proxies [\#537](https://github.com/nsubstitute/NSubstitute/pull/537) ([zvirja](https://github.com/zvirja))
- Improve NSubstitute performance [\#536](https://github.com/nsubstitute/NSubstitute/pull/536) ([zvirja](https://github.com/zvirja))
- Added Nuget badge for README [\#531](https://github.com/nsubstitute/NSubstitute/pull/531) ([304NotModified](https://github.com/304NotModified))
- Improve Code fences [\#530](https://github.com/nsubstitute/NSubstitute/pull/530) ([304NotModified](https://github.com/304NotModified))
- Correctly format nested generic type name [\#527](https://github.com/nsubstitute/NSubstitute/pull/527) ([zvirja](https://github.com/zvirja))
- Code fences in docs [\#526](https://github.com/nsubstitute/NSubstitute/pull/526) ([dtchepak](https://github.com/dtchepak))
- Corrected to non-virtual instead of virtual [\#516](https://github.com/nsubstitute/NSubstitute/pull/516) ([MNF](https://github.com/MNF))
- Only instantiate relatedCalls if required [\#514](https://github.com/nsubstitute/NSubstitute/pull/514) ([dtchepak](https://github.com/dtchepak))
- Fix customizations might be ignored by NSubContainer [\#513](https://github.com/nsubstitute/NSubstitute/pull/513) ([zvirja](https://github.com/zvirja))
- Http links to https, updated dead links [\#512](https://github.com/nsubstitute/NSubstitute/pull/512) ([304NotModified](https://github.com/304NotModified))
- Include website artifact in appveyor build [\#511](https://github.com/nsubstitute/NSubstitute/pull/511) ([dtchepak](https://github.com/dtchepak))
- Switch website and code references to https [\#509](https://github.com/nsubstitute/NSubstitute/pull/509) ([dtchepak](https://github.com/dtchepak))
- Links to https in readme [\#504](https://github.com/nsubstitute/NSubstitute/pull/504) ([304NotModified](https://github.com/304NotModified))

## [v4.0.0](https://github.com/nsubstitute/nsubstitute/tree/v4.0.0) (2019-01-29)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v4.0.0-rc1...v4.0.0)

**Closed issues:**

- Using Arg.Any\<T\>\(\) to conditionally check derived types causes return callback to run [\#491](https://github.com/nsubstitute/NSubstitute/issues/491)
- Documentation: Configure\(\) extension method not yet in production [\#486](https://github.com/nsubstitute/NSubstitute/issues/486)

**Merged pull requests:**

- Update CHANGELOG.md for 4.0.0 release [\#494](https://github.com/nsubstitute/NSubstitute/pull/494) ([dtchepak](https://github.com/dtchepak))
- Docs: Configure\(\) only available in 4.0 and above \(\#486\) [\#487](https://github.com/nsubstitute/NSubstitute/pull/487) ([dtchepak](https://github.com/dtchepak))

## [v4.0.0-rc1](https://github.com/nsubstitute/nsubstitute/tree/v4.0.0-rc1) (2018-11-19)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v3.1.0...v4.0.0-rc1)

**Fixed bugs:**

- Calling When on partial substitute fails for async methods [\#467](https://github.com/nsubstitute/NSubstitute/issues/467)
- The type is marked as eligible for type equivalence [\#431](https://github.com/nsubstitute/NSubstitute/issues/431)
- RobustThreadLocal leads to the failure due to null value [\#381](https://github.com/nsubstitute/NSubstitute/issues/381)
- Interface same name of methods problem  [\#372](https://github.com/nsubstitute/NSubstitute/issues/372)
- Arg.Any restriction fails for null reference [\#291](https://github.com/nsubstitute/NSubstitute/issues/291)
- .Returns\(\) with multiple return values does not work correctly the first time it's called [\#225](https://github.com/nsubstitute/NSubstitute/issues/225)

**Closed issues:**

- Callback not fired for void when Arg.Any passed [\#484](https://github.com/nsubstitute/NSubstitute/issues/484)
- Docs: update Analyzer docs [\#474](https://github.com/nsubstitute/NSubstitute/issues/474)
- Docs: update changelog with full change list for 4.0 [\#473](https://github.com/nsubstitute/NSubstitute/issues/473)
- Docs: Clarify \[Obsolete\] messages [\#472](https://github.com/nsubstitute/NSubstitute/issues/472)
- Documentation: document breaking change CS8153 when going to 4.0 [\#471](https://github.com/nsubstitute/NSubstitute/issues/471)
- Upgrade jekyll [\#464](https://github.com/nsubstitute/NSubstitute/issues/464)
- Consider enabling GitHub dependency analysis for NSubstitute repository [\#463](https://github.com/nsubstitute/NSubstitute/issues/463)
- Remove default, parameterless constructor constraint on virtual concrete mocks [\#461](https://github.com/nsubstitute/NSubstitute/issues/461)
- Recieved\(\) not recognizing matching call [\#460](https://github.com/nsubstitute/NSubstitute/issues/460)
- Cannot validate mock of method with out parameter received a call. [\#459](https://github.com/nsubstitute/NSubstitute/issues/459)
- Cleanup redundant interfaces \(e.g. IMixedArgumentSpecificationsFactory\) [\#456](https://github.com/nsubstitute/NSubstitute/issues/456)
- Does not match if mock out parameter name matches out parameter name in outer method [\#455](https://github.com/nsubstitute/NSubstitute/issues/455)
- Matching calls is acting weird when same argument is used but different properties between the calls [\#454](https://github.com/nsubstitute/NSubstitute/issues/454)
- Intermittent failure of DidNotReceive with `Expected to receive a call matching` [\#453](https://github.com/nsubstitute/NSubstitute/issues/453)
- Return from async function [\#451](https://github.com/nsubstitute/NSubstitute/issues/451)
- Support netstandard 2.0 directly [\#446](https://github.com/nsubstitute/NSubstitute/issues/446)
- Received.InOrder Missing Calls [\#443](https://github.com/nsubstitute/NSubstitute/issues/443)
- Using Substitute for a method that continuous caller won't invoke the Returns that was specified. [\#441](https://github.com/nsubstitute/NSubstitute/issues/441)
- Add function to reset SubstitionContext [\#439](https://github.com/nsubstitute/NSubstitute/issues/439)
- Custom Matchers problem explanation [\#438](https://github.com/nsubstitute/NSubstitute/issues/438)
- Documentation: add `virtual` requirement to Getting Started and readme [\#437](https://github.com/nsubstitute/NSubstitute/issues/437)
- DidNotReceive\(\)/Receive\(\) with specific parameters check ignore the params [\#436](https://github.com/nsubstitute/NSubstitute/issues/436)
- Substitute returning null with AutoMapper [\#430](https://github.com/nsubstitute/NSubstitute/issues/430)
- Now that TypeScript 3 is out, I made this NSubstitute port [\#428](https://github.com/nsubstitute/NSubstitute/issues/428)
- Disabled interception in constructors lead to very confusing behavior [\#423](https://github.com/nsubstitute/NSubstitute/issues/423)
- CI: Test release only [\#422](https://github.com/nsubstitute/NSubstitute/issues/422)
- Castle.DynamicProxy TypeLoadException 'Foo' does not have an implementation [\#414](https://github.com/nsubstitute/NSubstitute/issues/414)
- Update CI builds to also run tests from the documentation [\#413](https://github.com/nsubstitute/NSubstitute/issues/413)
- Docs: Update docs to include NSubstitute.Analyzers info [\#411](https://github.com/nsubstitute/NSubstitute/issues/411)
- Docs: Update non-virtual members warning [\#409](https://github.com/nsubstitute/NSubstitute/issues/409)
- Add API to call base method for non-partial proxy [\#405](https://github.com/nsubstitute/NSubstitute/issues/405)
- Replacing Return values/callbacks doesn't always work [\#402](https://github.com/nsubstitute/NSubstitute/issues/402)
- Add support for the `out` and `ref` parameters matchers [\#401](https://github.com/nsubstitute/NSubstitute/issues/401)
- Improve ambiguous args message [\#400](https://github.com/nsubstitute/NSubstitute/issues/400)
- Document out parameters & arg matchers [\#399](https://github.com/nsubstitute/NSubstitute/issues/399)
- Feature request for Returns Extension. [\#397](https://github.com/nsubstitute/NSubstitute/issues/397)
- Improve interface proxy generation performance [\#394](https://github.com/nsubstitute/NSubstitute/issues/394)
- Argument matcher of received call does not match object state during call [\#392](https://github.com/nsubstitute/NSubstitute/issues/392)
- Checking a received call for a string argument value fails for identical strings [\#384](https://github.com/nsubstitute/NSubstitute/issues/384)
- Unable to mock interfaces that consume value types by reference [\#378](https://github.com/nsubstitute/NSubstitute/issues/378)
- Update documentation to suggest Configure\(\) method [\#377](https://github.com/nsubstitute/NSubstitute/issues/377)
- \[Unity3d\] Expression-bodied members is a problem for Unity3d [\#360](https://github.com/nsubstitute/NSubstitute/issues/360)
- Remove NSubstitute.Experimental.Received in v4 [\#351](https://github.com/nsubstitute/NSubstitute/issues/351)
- Add ability to use the specifying route for methods without args [\#350](https://github.com/nsubstitute/NSubstitute/issues/350)
- Please expose `sub.Received\(quantity\)` [\#348](https://github.com/nsubstitute/NSubstitute/issues/348)
- Publish XML documentation with nuget package [\#345](https://github.com/nsubstitute/NSubstitute/issues/345)
- Update footer on the main doc page [\#342](https://github.com/nsubstitute/NSubstitute/issues/342)
- Add back .NET 4.0 target to NSub 3.x [\#341](https://github.com/nsubstitute/NSubstitute/issues/341)
- Mocking of the nested property call [\#340](https://github.com/nsubstitute/NSubstitute/issues/340)
- Subscribes automatically to events [\#337](https://github.com/nsubstitute/NSubstitute/issues/337)
- Consider removing the Extensions.Zip\(\) method or make it internal [\#336](https://github.com/nsubstitute/NSubstitute/issues/336)
- Arg.Out, ReturnsLate feature request [\#333](https://github.com/nsubstitute/NSubstitute/issues/333)
- Look at restoring pre-NET46 targets for 3.x [\#329](https://github.com/nsubstitute/NSubstitute/issues/329)
- Code analyzers feature [\#328](https://github.com/nsubstitute/NSubstitute/issues/328)
- Add test for signing [\#327](https://github.com/nsubstitute/NSubstitute/issues/327)
- Should throw on unused arg matchers [\#279](https://github.com/nsubstitute/NSubstitute/issues/279)
- Add `Arg.IsNot` \(was "Can't replace a `Return` that throws"\) [\#254](https://github.com/nsubstitute/NSubstitute/issues/254)
- Substitute.For delegate much slower than for interfaces and classes [\#248](https://github.com/nsubstitute/NSubstitute/issues/248)
- Ability to set current SubstitutionContext in a thread-safe manner [\#220](https://github.com/nsubstitute/NSubstitute/issues/220)
- Substitute operation definition with overlapping cases  [\#177](https://github.com/nsubstitute/NSubstitute/issues/177)
- Allow direct use of SubstituteFactory [\#150](https://github.com/nsubstitute/NSubstitute/issues/150)
- Don't execute Returns actions while configuring a call [\#146](https://github.com/nsubstitute/NSubstitute/issues/146)
- Additional Args on stack should throw good exception [\#89](https://github.com/nsubstitute/NSubstitute/issues/89)

**Merged pull requests:**

- Document arg matchers in expression trees [\#483](https://github.com/nsubstitute/NSubstitute/pull/483) ([dtchepak](https://github.com/dtchepak))
- Change link to Travis CI [\#481](https://github.com/nsubstitute/NSubstitute/pull/481) ([zvirja](https://github.com/zvirja))
- Add a few important entries to the change log [\#479](https://github.com/nsubstitute/NSubstitute/pull/479) ([zvirja](https://github.com/zvirja))
- Clarify obsolete messages in SubstitutionContext [\#478](https://github.com/nsubstitute/NSubstitute/pull/478) ([dtchepak](https://github.com/dtchepak))
- Add support for custom IArgumentMatcher\<T\> [\#477](https://github.com/nsubstitute/NSubstitute/pull/477) ([zvirja](https://github.com/zvirja))
- Doc updates v4 [\#476](https://github.com/nsubstitute/NSubstitute/pull/476) ([dtchepak](https://github.com/dtchepak))
- Add CompatArgInstance for aiding migration to v4.0 [\#475](https://github.com/nsubstitute/NSubstitute/pull/475) ([dtchepak](https://github.com/dtchepak))
- Improve version calculation in build scripts [\#470](https://github.com/nsubstitute/NSubstitute/pull/470) ([zvirja](https://github.com/zvirja))
- Add When\(\) extensions for async methods [\#468](https://github.com/nsubstitute/NSubstitute/pull/468) ([zvirja](https://github.com/zvirja))
- Publish NuGet package as build artifact [\#466](https://github.com/nsubstitute/NSubstitute/pull/466) ([zvirja](https://github.com/zvirja))
- Jekyll upgrade [\#465](https://github.com/nsubstitute/NSubstitute/pull/465) ([dtchepak](https://github.com/dtchepak))
- Make next route configuration thread local [\#462](https://github.com/nsubstitute/NSubstitute/pull/462) ([zvirja](https://github.com/zvirja))
- Remove non used code and close internal extensions [\#458](https://github.com/nsubstitute/NSubstitute/pull/458) ([zvirja](https://github.com/zvirja))
- Reorganize ArgumentSpecification factories to simplify tree [\#457](https://github.com/nsubstitute/NSubstitute/pull/457) ([zvirja](https://github.com/zvirja))
- Docs: out/ref arg matchers, CompatArg, non-virtuals warning [\#452](https://github.com/nsubstitute/NSubstitute/pull/452) ([dtchepak](https://github.com/dtchepak))
- Add feature to call base for the specified methods [\#449](https://github.com/nsubstitute/NSubstitute/pull/449) ([zvirja](https://github.com/zvirja))
- Add dependency injection to easily customize NSubstitute [\#448](https://github.com/nsubstitute/NSubstitute/pull/448) ([zvirja](https://github.com/zvirja))
- Support .NET Standard 2.0 directly [\#447](https://github.com/nsubstitute/NSubstitute/pull/447) ([zvirja](https://github.com/zvirja))
- Reuse CallResults implementation for type results [\#435](https://github.com/nsubstitute/NSubstitute/pull/435) ([zvirja](https://github.com/zvirja))
- Remove SequenceNumberGenerator from SubstituteState [\#434](https://github.com/nsubstitute/NSubstitute/pull/434) ([zvirja](https://github.com/zvirja))
- Add issue templates [\#432](https://github.com/nsubstitute/NSubstitute/pull/432) ([dtchepak](https://github.com/dtchepak))
- Fail if base call configuration is illegal [\#429](https://github.com/nsubstitute/NSubstitute/pull/429) ([zvirja](https://github.com/zvirja))
- Always generate delegate containers in unique scope [\#427](https://github.com/nsubstitute/NSubstitute/pull/427) ([zvirja](https://github.com/zvirja))
- Call base members before proxy is fully initialized [\#425](https://github.com/nsubstitute/NSubstitute/pull/425) ([zvirja](https://github.com/zvirja))
- Run only Release build on CI [\#424](https://github.com/nsubstitute/NSubstitute/pull/424) ([zvirja](https://github.com/zvirja))
- Use statically defined IsReadOnlyAttribute type [\#421](https://github.com/nsubstitute/NSubstitute/pull/421) ([zvirja](https://github.com/zvirja))
- Ensure parameters with 'in' modifier cannot be modified [\#420](https://github.com/nsubstitute/NSubstitute/pull/420) ([zvirja](https://github.com/zvirja))
- Allow to configure "Call Base" feature at runtime [\#419](https://github.com/nsubstitute/NSubstitute/pull/419) ([zvirja](https://github.com/zvirja))
- Remove obsolete build scripts from solution [\#418](https://github.com/nsubstitute/NSubstitute/pull/418) ([zvirja](https://github.com/zvirja))
- Improve build scripts [\#417](https://github.com/nsubstitute/NSubstitute/pull/417) ([zvirja](https://github.com/zvirja))
- Ignore generated doc site and VIM tmp files [\#416](https://github.com/nsubstitute/NSubstitute/pull/416) ([zvirja](https://github.com/zvirja))
- Add analyser links to readme, and updated support options [\#415](https://github.com/nsubstitute/NSubstitute/pull/415) ([dtchepak](https://github.com/dtchepak))
- Updating docs with Configure\(\) and analysers info [\#412](https://github.com/nsubstitute/NSubstitute/pull/412) ([dtchepak](https://github.com/dtchepak))
- Docs: Update non-virtual members warning [\#410](https://github.com/nsubstitute/NSubstitute/pull/410) ([dtchepak](https://github.com/dtchepak))
- Update to Castle.Core 4.3.0 [\#408](https://github.com/nsubstitute/NSubstitute/pull/408) ([dtchepak](https://github.com/dtchepak))
- Update NUnit to correctly report explicit tests [\#406](https://github.com/nsubstitute/NSubstitute/pull/406) ([zvirja](https://github.com/zvirja))
- Support argument matchers for by ref args [\#404](https://github.com/nsubstitute/NSubstitute/pull/404) ([zvirja](https://github.com/zvirja))
- Improve ambiguous exception diagnostics capabilities [\#403](https://github.com/nsubstitute/NSubstitute/pull/403) ([zvirja](https://github.com/zvirja))
- Adding benchmarks build target [\#398](https://github.com/nsubstitute/NSubstitute/pull/398) ([dtchepak](https://github.com/dtchepak))
- Add project with common benchmarks [\#396](https://github.com/nsubstitute/NSubstitute/pull/396) ([zvirja](https://github.com/zvirja))
- Optimize array allocation to boost the proxy activation performance [\#395](https://github.com/nsubstitute/NSubstitute/pull/395) ([zvirja](https://github.com/zvirja))
- Add quick test whether method is event/property part [\#391](https://github.com/nsubstitute/NSubstitute/pull/391) ([zvirja](https://github.com/zvirja))
- Minor performance improvements [\#390](https://github.com/nsubstitute/NSubstitute/pull/390) ([zvirja](https://github.com/zvirja))
- Create IAutoValueProvider factory with all supported providers [\#389](https://github.com/nsubstitute/NSubstitute/pull/389) ([zvirja](https://github.com/zvirja))
- Cleanup SubstituteState from members not related to state [\#388](https://github.com/nsubstitute/NSubstitute/pull/388) ([zvirja](https://github.com/zvirja))
- Remove non-used PendingSpecificationInfo property [\#387](https://github.com/nsubstitute/NSubstitute/pull/387) ([zvirja](https://github.com/zvirja))
- Allow to run arbitrary queries on ThreadLocalContext [\#386](https://github.com/nsubstitute/NSubstitute/pull/386) ([zvirja](https://github.com/zvirja))
- Verify assembly is always signed [\#385](https://github.com/nsubstitute/NSubstitute/pull/385) ([zvirja](https://github.com/zvirja))
- Refactor SubstituteContext to decouple the thread local context [\#383](https://github.com/nsubstitute/NSubstitute/pull/383) ([zvirja](https://github.com/zvirja))
- Fix ArgumentNullException on the finalizer thread [\#382](https://github.com/nsubstitute/NSubstitute/pull/382) ([zvirja](https://github.com/zvirja))
- Improve delegate proxy generation [\#380](https://github.com/nsubstitute/NSubstitute/pull/380) ([zvirja](https://github.com/zvirja))
- Introduce proxy id to simplify identification [\#379](https://github.com/nsubstitute/NSubstitute/pull/379) ([zvirja](https://github.com/zvirja))
- Add synchronization to delegate wrapper builder [\#376](https://github.com/nsubstitute/NSubstitute/pull/376) ([zvirja](https://github.com/zvirja))
- Use original arguments when modified value is not required [\#375](https://github.com/nsubstitute/NSubstitute/pull/375) ([zvirja](https://github.com/zvirja))
- Limit Castle Core to 4.2.1 which has fix for \#372 [\#374](https://github.com/nsubstitute/NSubstitute/pull/374) ([alexandrnikitin](https://github.com/alexandrnikitin))
- Add EditorConfig file [\#370](https://github.com/nsubstitute/NSubstitute/pull/370) ([zvirja](https://github.com/zvirja))
- Swap params [\#369](https://github.com/nsubstitute/NSubstitute/pull/369) ([jiimaho](https://github.com/jiimaho))
- Add tests for substituted properties that used as argument matchers [\#367](https://github.com/nsubstitute/NSubstitute/pull/367) ([alexandrnikitin](https://github.com/alexandrnikitin))
- Doc update 4x [\#366](https://github.com/nsubstitute/NSubstitute/pull/366) ([dtchepak](https://github.com/dtchepak))
- Refactor CallRouter for better readability [\#364](https://github.com/nsubstitute/NSubstitute/pull/364) ([zvirja](https://github.com/zvirja))
- Refactor primary type lookup logic for better readability [\#363](https://github.com/nsubstitute/NSubstitute/pull/363) ([zvirja](https://github.com/zvirja))
- Rework delegate proxy generation approach to improve performance [\#362](https://github.com/nsubstitute/NSubstitute/pull/362) ([zvirja](https://github.com/zvirja))
- Improve pending specifications diagnostics [\#361](https://github.com/nsubstitute/NSubstitute/pull/361) ([zvirja](https://github.com/zvirja))
- Expose sub.Received\(Quantity\) extension method \(\#348\) [\#359](https://github.com/nsubstitute/NSubstitute/pull/359) ([dtchepak](https://github.com/dtchepak))
- Refactor ICall creation and argument matchers queue usage [\#356](https://github.com/nsubstitute/NSubstitute/pull/356) ([zvirja](https://github.com/zvirja))
- Optimize CallResults to perform single lookup for result instead of two [\#355](https://github.com/nsubstitute/NSubstitute/pull/355) ([zvirja](https://github.com/zvirja))
- Improve MatchArg debug display [\#354](https://github.com/nsubstitute/NSubstitute/pull/354) ([zvirja](https://github.com/zvirja))
- Fix one configuration could prevent from other configuration [\#347](https://github.com/nsubstitute/NSubstitute/pull/347) ([zvirja](https://github.com/zvirja))
- Fix Travis CI build [\#343](https://github.com/nsubstitute/NSubstitute/pull/343) ([alexandrnikitin](https://github.com/alexandrnikitin))
- Fix broken link [\#339](https://github.com/nsubstitute/NSubstitute/pull/339) ([ChrisMaddock](https://github.com/ChrisMaddock))
- Doc: Sample for event invocation check [\#338](https://github.com/nsubstitute/NSubstitute/pull/338) ([jsbed](https://github.com/jsbed))

## [v3.1.0](https://github.com/nsubstitute/nsubstitute/tree/v3.1.0) (2017-10-27)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v3.0.1...v3.1.0)

**Fixed bugs:**

- Could not load file or assembly NSubstitute [\#332](https://github.com/nsubstitute/NSubstitute/issues/332)

**Closed issues:**

- Calling stubbed methods with out params only works once [\#334](https://github.com/nsubstitute/NSubstitute/issues/334)
- upgrading v2 -\> v3 adds lots of noise to my csproj and config files [\#331](https://github.com/nsubstitute/NSubstitute/issues/331)
- Fix travis-ci build -- signing [\#326](https://github.com/nsubstitute/NSubstitute/issues/326)
- \[Critical\] NSubstitute 3.0 is not signed [\#324](https://github.com/nsubstitute/NSubstitute/issues/324)
- NSubstitue with Received isn't working correctly in .Net Core 2 [\#321](https://github.com/nsubstitute/NSubstitute/issues/321)

**Merged pull requests:**

- Adding support for net45 to 3.x \(\#329\) [\#330](https://github.com/nsubstitute/NSubstitute/pull/330) ([dtchepak](https://github.com/dtchepak))
- Support for returning ValueTask\<T\> results. [\#325](https://github.com/nsubstitute/NSubstitute/pull/325) ([KrzysztofBranicki](https://github.com/KrzysztofBranicki))

## [v3.0.1](https://github.com/nsubstitute/nsubstitute/tree/v3.0.1) (2017-10-08)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v3.0.0...v3.0.1)

**Closed issues:**

- Update build after migration to netstandard-1.3 [\#319](https://github.com/nsubstitute/NSubstitute/issues/319)
- I just upgraded to Castle Core v4.2.0 and I am getting an assembly binding error [\#317](https://github.com/nsubstitute/NSubstitute/issues/317)
- Using Arg.Any\<Func\<in T, out TResult\>\> in Received throws NullReferenceException [\#312](https://github.com/nsubstitute/NSubstitute/issues/312)
- Clearing `DoNotCallBase` [\#309](https://github.com/nsubstitute/NSubstitute/issues/309)
- System.Reflection.ReflectionTypeLoadException on parallelized NUnit tests [\#307](https://github.com/nsubstitute/NSubstitute/issues/307)
- Fake db context which is invoked inside query handler [\#285](https://github.com/nsubstitute/NSubstitute/issues/285)
- Checking if method received with Arg.Any\<string\>\(\) parameter, NSubstitute expects \<null\> [\#278](https://github.com/nsubstitute/NSubstitute/issues/278)
- Add info to AmbiguousArgumentsException [\#262](https://github.com/nsubstitute/NSubstitute/issues/262)
- How to get ICallSpecification from ReceivedCalls\(\) / ICall [\#253](https://github.com/nsubstitute/NSubstitute/issues/253)
- Implicitly implement substituted interfaces [\#250](https://github.com/nsubstitute/NSubstitute/issues/250)
- DynamicProxyGenAssembly2 hardcoded name [\#249](https://github.com/nsubstitute/NSubstitute/issues/249)
- .NET Core - HttpWebRequest [\#245](https://github.com/nsubstitute/NSubstitute/issues/245)
- Issue Generating Generic Substitute where the generic doesn't have a specific definition [\#240](https://github.com/nsubstitute/NSubstitute/issues/240)
- Portable Class Library support [\#236](https://github.com/nsubstitute/NSubstitute/issues/236)
- Issue using NSubstitute with AutoFixture and parallel tests execution [\#227](https://github.com/nsubstitute/NSubstitute/issues/227)
- Unexpected behaviour with public non-virtual method that uses a protected virtual method [\#223](https://github.com/nsubstitute/NSubstitute/issues/223)
- Is it possible to fake a protected virtual method? [\#222](https://github.com/nsubstitute/NSubstitute/issues/222)
- Received\(\) fails if values of output arguments are not right [\#221](https://github.com/nsubstitute/NSubstitute/issues/221)
- Unable to return value from another substitute [\#217](https://github.com/nsubstitute/NSubstitute/issues/217)
- Configuring return values for a substitute created with ForPartsOf registers a received call [\#213](https://github.com/nsubstitute/NSubstitute/issues/213)
- Initial mock creation takes long time [\#206](https://github.com/nsubstitute/NSubstitute/issues/206)
- ForPartsOf\<T\> doesn't run real code in constructor [\#188](https://github.com/nsubstitute/NSubstitute/issues/188)
- Introdce a ReturnsMany\(\) extension method to be able to substitute an IEnumerable of an interface [\#184](https://github.com/nsubstitute/NSubstitute/issues/184)
- Substitute.For\(typesToProxy, constructorArguments\) throws ArrayTypeMismatchException on Mono [\#174](https://github.com/nsubstitute/NSubstitute/issues/174)
- Argument matchers cause side effects when used for nothing [\#167](https://github.com/nsubstitute/NSubstitute/issues/167)
- Non virtual methods on a class automatically pass in testing framework .Received\(\).XXX is called. [\#166](https://github.com/nsubstitute/NSubstitute/issues/166)
- Better support for delegates would be nice [\#131](https://github.com/nsubstitute/NSubstitute/issues/131)
- Raising event on substituted class fails [\#121](https://github.com/nsubstitute/NSubstitute/issues/121)
- ArgumentNullException while mocking a large interface in a unit test project [\#120](https://github.com/nsubstitute/NSubstitute/issues/120)
- Clearing Out All Substitutions [\#106](https://github.com/nsubstitute/NSubstitute/issues/106)
- Generate diagnostic when trying to call Received on a non-virtual method [\#105](https://github.com/nsubstitute/NSubstitute/issues/105)
- Exception should be thrown when trying to apply Returns on something that isn't a substitute [\#104](https://github.com/nsubstitute/NSubstitute/issues/104)
- If one interface implements another interface and both contains the same property the property is not set on the original object that implements the first interface [\#95](https://github.com/nsubstitute/NSubstitute/issues/95)
- Conflicting Castle reference [\#86](https://github.com/nsubstitute/NSubstitute/issues/86)
- Add extension point for substitute initialization [\#85](https://github.com/nsubstitute/NSubstitute/issues/85)
- .Net 4.5 assembly / Windows 8 apps [\#82](https://github.com/nsubstitute/NSubstitute/issues/82)
- OOM with large Interop's [\#74](https://github.com/nsubstitute/NSubstitute/issues/74)

**Merged pull requests:**

- Change .txt to md files for better visualization [\#322](https://github.com/nsubstitute/NSubstitute/pull/322) ([StefanKert](https://github.com/StefanKert))

## [v3.0.0](https://github.com/nsubstitute/nsubstitute/tree/v3.0.0) (2017-10-06)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v2.0.3...v3.0.0)

**Closed issues:**

- Upgrade Castle.Core to 4.1.0 [\#315](https://github.com/nsubstitute/NSubstitute/issues/315)
- Convenient method to get arguments by which a call is made  [\#313](https://github.com/nsubstitute/NSubstitute/issues/313)
- System.ComponentModel.TypeConverter 4.0.1 was not found [\#310](https://github.com/nsubstitute/NSubstitute/issues/310)
- Mocking async methods in partial mocks throws NullReferenceException [\#308](https://github.com/nsubstitute/NSubstitute/issues/308)
- out arguments not working in 2.0.3 [\#305](https://github.com/nsubstitute/NSubstitute/issues/305)
- .NET Core support [\#301](https://github.com/nsubstitute/NSubstitute/issues/301)
- Redundant dependencies for .NET 4.6.2 projects [\#295](https://github.com/nsubstitute/NSubstitute/issues/295)
- Received Calls doesn't work [\#284](https://github.com/nsubstitute/NSubstitute/issues/284)
- Sync netcore and .NET projects [\#246](https://github.com/nsubstitute/NSubstitute/issues/246)
- Extension methods don't work for dynamic returns [\#144](https://github.com/nsubstitute/NSubstitute/issues/144)

**Merged pull requests:**

- 3.0 prep [\#320](https://github.com/nsubstitute/NSubstitute/pull/320) ([dtchepak](https://github.com/dtchepak))
- Fixes warning System.ComponentModel.TypeConverter 4.0.1 was not found [\#311](https://github.com/nsubstitute/NSubstitute/pull/311) ([StefanKert](https://github.com/StefanKert))
- Refactor .NET Core support [\#306](https://github.com/nsubstitute/NSubstitute/pull/306) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v2.0.3](https://github.com/nsubstitute/nsubstitute/tree/v2.0.3) (2017-04-25)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v2.0.2...v2.0.3)

**Closed issues:**

- Mono:Update to latest version and getting this error on the build. [\#299](https://github.com/nsubstitute/NSubstitute/issues/299)
- Update to latest version and getting this error on the build. [\#298](https://github.com/nsubstitute/NSubstitute/issues/298)
- Integration with Autofac \(or other container\) [\#292](https://github.com/nsubstitute/NSubstitute/issues/292)
- requiredcodeblock not displaying on Docs website [\#290](https://github.com/nsubstitute/NSubstitute/issues/290)
- does a mock by example feature exist? [\#289](https://github.com/nsubstitute/NSubstitute/issues/289)
- IOrderedEnumerable\<Generic\> argument gives AmbiguousArgumentsException [\#288](https://github.com/nsubstitute/NSubstitute/issues/288)
- The type initializer for 'NSubstitute.Core.SubstitutionContext' threw an exception. [\#287](https://github.com/nsubstitute/NSubstitute/issues/287)
- 2.0.1 release [\#286](https://github.com/nsubstitute/NSubstitute/issues/286)
- Issue with returning multiple values for Async Methods [\#282](https://github.com/nsubstitute/NSubstitute/issues/282)
- UWP Support [\#303](https://github.com/nsubstitute/NSubstitute/issues/303)

**Merged pull requests:**

- changing to netstandard 1.3 [\#304](https://github.com/nsubstitute/NSubstitute/pull/304) ([ipjohnson](https://github.com/ipjohnson))
- Fix AppVeyor CI [\#297](https://github.com/nsubstitute/NSubstitute/pull/297) ([alexandrnikitin](https://github.com/alexandrnikitin))
- Thread-safe implementation of ReturnMultipleValues.  [\#294](https://github.com/nsubstitute/NSubstitute/pull/294) ([jbialobr](https://github.com/jbialobr))
- Update notice on recursive substitutes and classes [\#293](https://github.com/nsubstitute/NSubstitute/pull/293) ([dsolovay](https://github.com/dsolovay))

## [v2.0.2](https://github.com/nsubstitute/nsubstitute/tree/v2.0.2) (2017-02-27)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/rc2.0.1...v2.0.2)

**Closed issues:**

- NSubstitute + AppVeyor + XUnit error : some predicates not called ? [\#281](https://github.com/nsubstitute/NSubstitute/issues/281)
- Unexpected behavior of .Received\(\). [\#280](https://github.com/nsubstitute/NSubstitute/issues/280)
- Delegate substitute does not set out parameter values [\#271](https://github.com/nsubstitute/NSubstitute/issues/271)
- NullReferenceException when using ReturnsNull on an method returning a Task [\#270](https://github.com/nsubstitute/NSubstitute/issues/270)
- .Returns fires all delegates registered previously on Substitute [\#268](https://github.com/nsubstitute/NSubstitute/issues/268)
- Intermittent AmbiguousArgumentsException when running tests in parallel [\#260](https://github.com/nsubstitute/NSubstitute/issues/260)

**Merged pull requests:**

- Add ReturnsNull support for methods returning tasks [\#277](https://github.com/nsubstitute/NSubstitute/pull/277) ([michael-wolfenden](https://github.com/michael-wolfenden))
- Fix a typo \(secenarios\) in callbacks doc [\#274](https://github.com/nsubstitute/NSubstitute/pull/274) ([christianrondeau](https://github.com/christianrondeau))
- Fixes delegates out/ref parameters [\#273](https://github.com/nsubstitute/NSubstitute/pull/273) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [rc2.0.1](https://github.com/nsubstitute/nsubstitute/tree/rc2.0.1) (2016-12-17)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/rc2.0.0...rc2.0.1)

**Closed issues:**

- Returns with matching arguments does not work when debugging test or during isolated execution [\#267](https://github.com/nsubstitute/NSubstitute/issues/267)
- Possibility to provide a setup action in Substitute.For [\#266](https://github.com/nsubstitute/NSubstitute/issues/266)
- Question: Why default route is recreated for each time?  [\#263](https://github.com/nsubstitute/NSubstitute/issues/263)
- Cannot check received when mock is called from method with out parameter [\#258](https://github.com/nsubstitute/NSubstitute/issues/258)
- Substitute for method with Expression\<Func\<T,\>\> parameters won't work [\#257](https://github.com/nsubstitute/NSubstitute/issues/257)
- Threading issue with CallRouter. [\#256](https://github.com/nsubstitute/NSubstitute/issues/256)
- Use newer NUnit version [\#255](https://github.com/nsubstitute/NSubstitute/issues/255)
- Does a Substitute with Return needs a recieved definition also when confirming the call?? [\#252](https://github.com/nsubstitute/NSubstitute/issues/252)
- CallInfo caller [\#251](https://github.com/nsubstitute/NSubstitute/issues/251)
- Abstract class substitution testing Received with Arg.Any on an interface with parameters [\#247](https://github.com/nsubstitute/NSubstitute/issues/247)
- How to build NSubstitute.csproj for local testing purpose? [\#244](https://github.com/nsubstitute/NSubstitute/issues/244)
- Support for .NET Core [\#192](https://github.com/nsubstitute/NSubstitute/issues/192)
- Remove build dependency on Rake [\#180](https://github.com/nsubstitute/NSubstitute/issues/180)

**Merged pull requests:**

- Fix Travis CI OSX build [\#265](https://github.com/nsubstitute/NSubstitute/pull/265) ([alexandrnikitin](https://github.com/alexandrnikitin))
- Castlecore 4.0.0 beta002 [\#261](https://github.com/nsubstitute/NSubstitute/pull/261) ([dtchepak](https://github.com/dtchepak))
- Add extensibility point for custom auto providers [\#259](https://github.com/nsubstitute/NSubstitute/pull/259) ([zvirja](https://github.com/zvirja))

## [rc2.0.0](https://github.com/nsubstitute/nsubstitute/tree/rc2.0.0) (2016-08-07)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.10.0...rc2.0.0)

**Closed issues:**

- Oddness with IList\<T\> mocks. [\#241](https://github.com/nsubstitute/NSubstitute/issues/241)
- Received InOrder breaks other tests when an error occurs [\#237](https://github.com/nsubstitute/NSubstitute/issues/237)
- can't clear Arg.Do\<T\>\(\(\) =\> {}\) [\#235](https://github.com/nsubstitute/NSubstitute/issues/235)
- Framework 4.6.1 support [\#232](https://github.com/nsubstitute/NSubstitute/issues/232)
- Received\(\) doesn't fail if argument used is returned by substitute itself [\#230](https://github.com/nsubstitute/NSubstitute/issues/230)
- Out parameter requires resetting before subsequent calls will match 'Returns' argument matcher. [\#229](https://github.com/nsubstitute/NSubstitute/issues/229)
- NSubstitute .Received\(\) does not failed when checking extension method call [\#228](https://github.com/nsubstitute/NSubstitute/issues/228)
- Support returning empty collections for new collection interfaces in 4.5 [\#154](https://github.com/nsubstitute/NSubstitute/issues/154)
- Ability to use add reason for a check [\#108](https://github.com/nsubstitute/NSubstitute/issues/108)
- Verifying event subscriptions [\#107](https://github.com/nsubstitute/NSubstitute/issues/107)

**Merged pull requests:**

- Resolve issue 237 by wrapping method callsin try finally. [\#238](https://github.com/nsubstitute/NSubstitute/pull/238) ([m3zercat](https://github.com/m3zercat))
- Document that the position for ArgAt is zero-based [\#231](https://github.com/nsubstitute/NSubstitute/pull/231) ([asbjornu](https://github.com/asbjornu))
- .NET Core support [\#197](https://github.com/nsubstitute/NSubstitute/pull/197) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v1.10.0](https://github.com/nsubstitute/nsubstitute/tree/v1.10.0) (2016-03-30)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.9.2...v1.10.0)

**Closed issues:**

- Does NSubstitute Support Strict Mode or going to? [\#219](https://github.com/nsubstitute/NSubstitute/issues/219)
- IDisposable mocking [\#218](https://github.com/nsubstitute/NSubstitute/issues/218)
- Received and Arg.Is\<object\> [\#216](https://github.com/nsubstitute/NSubstitute/issues/216)
- Bug Set\_out\_argument\_via\_returns when out arg not null [\#215](https://github.com/nsubstitute/NSubstitute/issues/215)
- Params arguments not formatting for values types like `params int\[\]` [\#214](https://github.com/nsubstitute/NSubstitute/issues/214)
- Reseting substitutes between tests [\#212](https://github.com/nsubstitute/NSubstitute/issues/212)
- CallSequenceNotFoundException should list details of params arguments [\#211](https://github.com/nsubstitute/NSubstitute/issues/211)
- Auto-mocking an IObservable pushes a value [\#210](https://github.com/nsubstitute/NSubstitute/issues/210)
- Problem with parallel substituting for delegates [\#205](https://github.com/nsubstitute/NSubstitute/issues/205)
- Auto-subbing from IQueryable [\#67](https://github.com/nsubstitute/NSubstitute/issues/67)

**Merged pull requests:**

- added new AutoQueryableProvider \(\#67\) [\#224](https://github.com/nsubstitute/NSubstitute/pull/224) ([emragins](https://github.com/emragins))

## [v1.9.2](https://github.com/nsubstitute/nsubstitute/tree/v1.9.2) (2015-10-22)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.9.1...v1.9.2)

**Closed issues:**

- Substitutes set up to throw exception for methods with return type Task\<T\> cause compilation error [\#208](https://github.com/nsubstitute/NSubstitute/issues/208)
- Random CouldNotSetReturnDueToTypeMismatchException [\#204](https://github.com/nsubstitute/NSubstitute/issues/204)

**Merged pull requests:**

- Updating BreakingChanges for 1.9.1 release. [\#209](https://github.com/nsubstitute/NSubstitute/pull/209) ([slashP](https://github.com/slashP))

## [v1.9.1](https://github.com/nsubstitute/nsubstitute/tree/v1.9.1) (2015-09-30)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.9.0...v1.9.1)

**Closed issues:**

- ReturnsForAll\<T\> documentation [\#199](https://github.com/nsubstitute/NSubstitute/issues/199)

## [v1.9.0](https://github.com/nsubstitute/nsubstitute/tree/v1.9.0) (2015-09-28)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.8.2...v1.9.0)

**Closed issues:**

- ReturnsForAll\<T\> [\#196](https://github.com/nsubstitute/NSubstitute/issues/196)
- NSubstitute in Unity Testing Tool and partial mocks [\#194](https://github.com/nsubstitute/NSubstitute/issues/194)
- Return non-null when using Received\(\) with async method [\#190](https://github.com/nsubstitute/NSubstitute/issues/190)
- Add ReturnsTaskResult for async methods [\#189](https://github.com/nsubstitute/NSubstitute/issues/189)
- Faking a call to an array for a particular index raises an exception [\#187](https://github.com/nsubstitute/NSubstitute/issues/187)
- Subsequent argument matchers return null when passed to CallInfo [\#186](https://github.com/nsubstitute/NSubstitute/issues/186)
- Extend CallInfo to have information about generics type on the call [\#185](https://github.com/nsubstitute/NSubstitute/issues/185)
- Returns\(\) not working as expected with Substitute.ForPartsOf\<T\>\(\) [\#159](https://github.com/nsubstitute/NSubstitute/issues/159)

**Merged pull requests:**

- Async methods can now be awaited after using Received and DidNotReceive. [\#191](https://github.com/nsubstitute/NSubstitute/pull/191) ([mrinaldi](https://github.com/mrinaldi))

## [v1.8.2](https://github.com/nsubstitute/nsubstitute/tree/v1.8.2) (2015-05-29)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.8.1...v1.8.2)

**Fixed bugs:**

- Checking received calls on base of partial sub [\#173](https://github.com/nsubstitute/NSubstitute/issues/173)

**Closed issues:**

- Argument matcher as variable causes false positive test [\#183](https://github.com/nsubstitute/NSubstitute/issues/183)
- NSubstitute throws when substituted type contains virtual event or is interface with event [\#182](https://github.com/nsubstitute/NSubstitute/issues/182)
- Make easy and safe to get typed parameter from CallInfo [\#175](https://github.com/nsubstitute/NSubstitute/issues/175)
- Proxy to target, or easy reset [\#157](https://github.com/nsubstitute/NSubstitute/issues/157)
- Easy way to return null [\#87](https://github.com/nsubstitute/NSubstitute/issues/87)

## [v1.8.1](https://github.com/nsubstitute/nsubstitute/tree/v1.8.1) (2014-12-26)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.8.0...v1.8.1)

**Closed issues:**

- Can't create a substitute for a method returning multidimensional array [\#170](https://github.com/nsubstitute/NSubstitute/issues/170)
- Allow passing multiple functions in WhenCalled.Do [\#169](https://github.com/nsubstitute/NSubstitute/issues/169)

**Merged pull requests:**

- Fixes Issue \#170 \(multidimensional array bug\) [\#171](https://github.com/nsubstitute/NSubstitute/pull/171) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v1.8.0](https://github.com/nsubstitute/nsubstitute/tree/v1.8.0) (2014-11-11)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.7.2...v1.8.0)

**Closed issues:**

- Optional arguments in constructor [\#165](https://github.com/nsubstitute/NSubstitute/issues/165)
- Using Arg.Any\<\>\(\) in .Returns\(\) causes unexpected behavior [\#149](https://github.com/nsubstitute/NSubstitute/issues/149)
- IEnumerable should return an empty array [\#148](https://github.com/nsubstitute/NSubstitute/issues/148)
- MSBuild All The Things [\#117](https://github.com/nsubstitute/NSubstitute/issues/117)
- Does not work with members that use dynamic [\#75](https://github.com/nsubstitute/NSubstitute/issues/75)
- Support for Partial Mocks [\#41](https://github.com/nsubstitute/NSubstitute/issues/41)

**Merged pull requests:**

- Added more convenient setup of throwing exceptions. [\#158](https://github.com/nsubstitute/NSubstitute/pull/158) ([geirsagberg](https://github.com/geirsagberg))
- Added a passing test for args passed by ref within \#129 [\#147](https://github.com/nsubstitute/NSubstitute/pull/147) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v1.7.2](https://github.com/nsubstitute/nsubstitute/tree/v1.7.2) (2014-03-03)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.7.1...v1.7.2)

**Closed issues:**

- Bug when using out parameter in an inline method call [\#142](https://github.com/nsubstitute/NSubstitute/issues/142)
- AmbiguousArgumentsException  with int out/ref arg [\#134](https://github.com/nsubstitute/NSubstitute/issues/134)
- Ambiguous args with out/ref arg [\#129](https://github.com/nsubstitute/NSubstitute/issues/129)

**Merged pull requests:**

- Issue 75 Does not work with members that use dynamic [\#141](https://github.com/nsubstitute/NSubstitute/pull/141) ([alexandrnikitin](https://github.com/alexandrnikitin))
- IObservable\<T\> should never return null [\#137](https://github.com/nsubstitute/NSubstitute/pull/137) ([anaisbetts](https://github.com/anaisbetts))
- Add .NET 4.5 Build [\#135](https://github.com/nsubstitute/NSubstitute/pull/135) ([anaisbetts](https://github.com/anaisbetts))

## [v1.7.1](https://github.com/nsubstitute/nsubstitute/tree/v1.7.1) (2014-01-16)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.7.0...v1.7.1)

**Closed issues:**

- DidNotReceive with Count [\#130](https://github.com/nsubstitute/NSubstitute/issues/130)
- Actually received no matching calls [\#109](https://github.com/nsubstitute/NSubstitute/issues/109)
- Partial mocking when unit testing a virtual method that calls another virtual method [\#93](https://github.com/nsubstitute/NSubstitute/issues/93)

**Merged pull requests:**

- \#129 Ambiguous args with out/ref arg [\#132](https://github.com/nsubstitute/NSubstitute/pull/132) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v1.7.0](https://github.com/nsubstitute/nsubstitute/tree/v1.7.0) (2014-01-03)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.6.1...v1.7.0)

**Closed issues:**

- BeCloseTo for timespan [\#128](https://github.com/nsubstitute/NSubstitute/issues/128)
- NSubstitute throws exception setting up return value when it's a sealed class with no public method [\#125](https://github.com/nsubstitute/NSubstitute/issues/125)
- Improve error message [\#124](https://github.com/nsubstitute/NSubstitute/issues/124)
- Mocking concrete classes with a public static method breaks the substitutes [\#118](https://github.com/nsubstitute/NSubstitute/issues/118)
- List parameters doesn´t detect received calls [\#115](https://github.com/nsubstitute/NSubstitute/issues/115)
- Args matches with optional parameters broken [\#114](https://github.com/nsubstitute/NSubstitute/issues/114)
- Args matches with out/ref broken [\#111](https://github.com/nsubstitute/NSubstitute/issues/111)
- NSubstitute can't produce proxys in Mono \(as requested\) [\#76](https://github.com/nsubstitute/NSubstitute/issues/76)

**Merged pull requests:**

- Fix for Issue 118 [\#119](https://github.com/nsubstitute/NSubstitute/pull/119) ([robdmoore](https://github.com/robdmoore))
- Possible issue with check of optional parameters [\#113](https://github.com/nsubstitute/NSubstitute/pull/113) ([alexandrnikitin](https://github.com/alexandrnikitin))

## [v1.6.1](https://github.com/nsubstitute/nsubstitute/tree/v1.6.1) (2013-06-30)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.6.0...v1.6.1)

**Closed issues:**

- SerializationException thrown on user exception in Raise.EventWith\(\) [\#110](https://github.com/nsubstitute/NSubstitute/issues/110)
- Allow chaining a callback method before the Returns call. [\#98](https://github.com/nsubstitute/NSubstitute/issues/98)

## [v1.6.0](https://github.com/nsubstitute/nsubstitute/tree/v1.6.0) (2013-04-19)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.5.0...v1.6.0)

**Closed issues:**

- TypeLoadException when debugging [\#96](https://github.com/nsubstitute/NSubstitute/issues/96)
- Automock Task/Task\<T\> [\#90](https://github.com/nsubstitute/NSubstitute/issues/90)
- Run tests over multiple framework version as part of build [\#29](https://github.com/nsubstitute/NSubstitute/issues/29)
- Out and ref parameters [\#21](https://github.com/nsubstitute/NSubstitute/issues/21)
- Query model for received calls [\#18](https://github.com/nsubstitute/NSubstitute/issues/18)
- Silverlight compatibility [\#17](https://github.com/nsubstitute/NSubstitute/issues/17)
- Ordered mocks [\#12](https://github.com/nsubstitute/NSubstitute/issues/12)

**Merged pull requests:**

- BUGFIX: Fixed handling of value-type params array parameters [\#102](https://github.com/nsubstitute/NSubstitute/pull/102) ([eric-winkler](https://github.com/eric-winkler))
- Adding UIPermissionAttribute to AttributesToAvoidReplicating used with Castle Dynamic Proxy. [\#101](https://github.com/nsubstitute/NSubstitute/pull/101) ([appel1](https://github.com/appel1))

## [v1.5.0](https://github.com/nsubstitute/nsubstitute/tree/v1.5.0) (2013-01-25)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.4.3...v1.5.0)

**Closed issues:**

- Return multiple results from collection of Funcs [\#99](https://github.com/nsubstitute/NSubstitute/issues/99)
- Argument matchers in class that overwrites Equals [\#77](https://github.com/nsubstitute/NSubstitute/issues/77)

**Merged pull requests:**

- Received\(\)... behavior for generic methods  [\#97](https://github.com/nsubstitute/NSubstitute/pull/97) ([i-e-b](https://github.com/i-e-b))
- Issue 77 PR [\#94](https://github.com/nsubstitute/NSubstitute/pull/94) ([robdmoore](https://github.com/robdmoore))

## [v1.4.3](https://github.com/nsubstitute/nsubstitute/tree/v1.4.3) (2012-08-15)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.4.2...v1.4.3)

**Closed issues:**

- Calls to generic methods with struct constraint [\#83](https://github.com/nsubstitute/NSubstitute/issues/83)
- ReturnsForAnyArgs seems to nolonger work for optional parameters [\#81](https://github.com/nsubstitute/NSubstitute/issues/81)

## [v1.4.2](https://github.com/nsubstitute/nsubstitute/tree/v1.4.2) (2012-07-01)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.4.1...v1.4.2)

## [v1.4.1](https://github.com/nsubstitute/nsubstitute/tree/v1.4.1) (2012-06-28)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.4.0...v1.4.1)

**Closed issues:**

- Nullable args broken [\#78](https://github.com/nsubstitute/NSubstitute/issues/78)

## [v1.4.0](https://github.com/nsubstitute/nsubstitute/tree/v1.4.0) (2012-05-04)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.3.0...v1.4.0)

**Fixed bugs:**

- Exception substituting for internal types of a friend assembly [\#69](https://github.com/nsubstitute/NSubstitute/issues/69)

**Closed issues:**

- Losing items from IEnumerable\<T\> [\#70](https://github.com/nsubstitute/NSubstitute/issues/70)
- Received\(\) should keep a copy arguments to the call [\#66](https://github.com/nsubstitute/NSubstitute/issues/66)
- ReceivedCallsException should list details of params arguments [\#65](https://github.com/nsubstitute/NSubstitute/issues/65)
- Race condition between checking received calls  [\#64](https://github.com/nsubstitute/NSubstitute/issues/64)
- Auto-subbing from Func delegates [\#52](https://github.com/nsubstitute/NSubstitute/issues/52)

## [v1.3.0](https://github.com/nsubstitute/nsubstitute/tree/v1.3.0) (2011-11-19)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.2.1...v1.3.0)

**Fixed bugs:**

- Multi-threaded calls to a substitute [\#62](https://github.com/nsubstitute/NSubstitute/issues/62)

**Closed issues:**

- Documentation \(ongoing\) [\#30](https://github.com/nsubstitute/NSubstitute/issues/30)

## [v1.2.1](https://github.com/nsubstitute/nsubstitute/tree/v1.2.1) (2011-10-10)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.2.0...v1.2.1)

**Fixed bugs:**

- Arg.Any\<subclass\>\(\) not overridden properly by ReturnsForAnyArgs\(\) [\#55](https://github.com/nsubstitute/NSubstitute/issues/55)
- Stub any string and pass null throws null ref from NSub \(1.2\) [\#61](https://github.com/nsubstitute/NSubstitute/issues/61)
- Avoid replicating ServiceContractAttribute [\#60](https://github.com/nsubstitute/NSubstitute/issues/60)
- Mixing Arg.Do with Returns for properties [\#59](https://github.com/nsubstitute/NSubstitute/issues/59)
- Setting virtual prop in ctor causes Returns to use auto-sub [\#57](https://github.com/nsubstitute/NSubstitute/issues/57)

**Closed issues:**

- 12 failing tests in the master branch [\#58](https://github.com/nsubstitute/NSubstitute/issues/58)

## [v1.2.0](https://github.com/nsubstitute/nsubstitute/tree/v1.2.0) (2011-09-05)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.1.0...v1.2.0)

**Fixed bugs:**

- Property behaviour for indexers don't work [\#53](https://github.com/nsubstitute/NSubstitute/issues/53)

**Closed issues:**

- NSubstitute CI Build [\#54](https://github.com/nsubstitute/NSubstitute/issues/54)
- nSubstitute fails when trying to substitute Microsoft.Office.Interop.Word.Application [\#43](https://github.com/nsubstitute/NSubstitute/issues/43)

**Merged pull requests:**

- compiling on mono [\#50](https://github.com/nsubstitute/NSubstitute/pull/50) ([pshomov](https://github.com/pshomov))

## [v1.1.0](https://github.com/nsubstitute/nsubstitute/tree/v1.1.0) (2011-05-21)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v1.0.0...v1.1.0)

**Fixed bugs:**

- Exception when using null parameter for raising events [\#47](https://github.com/nsubstitute/NSubstitute/issues/47)
- CallInfo.Arg\<T\>\(\) fails for null argument [\#45](https://github.com/nsubstitute/NSubstitute/issues/45)

**Closed issues:**

- Received\(\) and DidNotReceive\(\) should have decent error msgs when called on null [\#46](https://github.com/nsubstitute/NSubstitute/issues/46)

## [v1.0.0](https://github.com/nsubstitute/nsubstitute/tree/v1.0.0) (2010-12-21)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.9.5...v1.0.0)

## [v0.9.5](https://github.com/nsubstitute/nsubstitute/tree/v0.9.5) (2010-12-14)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.9.0...v0.9.5)

## [v0.9.0](https://github.com/nsubstitute/nsubstitute/tree/v0.9.0) (2010-09-21)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.1.3...v0.9.0)

## [v0.1.3](https://github.com/nsubstitute/nsubstitute/tree/v0.1.3) (2010-08-16)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.1.2...v0.1.3)

## [v0.1.2](https://github.com/nsubstitute/nsubstitute/tree/v0.1.2) (2010-07-16)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.1.1...v0.1.2)

## [v0.1.1](https://github.com/nsubstitute/nsubstitute/tree/v0.1.1) (2010-07-01)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.1.0...v0.1.1)

## [v0.1.0](https://github.com/nsubstitute/nsubstitute/tree/v0.1.0) (2010-06-28)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/v0.0.0...v0.1.0)

## [v0.0.0](https://github.com/nsubstitute/nsubstitute/tree/v0.0.0) (2009-07-27)

[Full Changelog](https://github.com/nsubstitute/nsubstitute/compare/b63bbd1eb8004a4c3a7ac1c48016ab3ce29bba89...v0.0.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*

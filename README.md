# Angular Interview Questions 

<img src="https://webref.ru/assets/images/angular-cookbook/angular.png" width="960">

### Table of Contents

| No. | Questions                                                                                                                                                                                    |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is Angular Framework?](#what-is-angular-framework)                                                                                                                                     |
| 2   | [What is the difference between AngularJS and Angular?](#what-is-the-difference-between-angularjs-and-angular)                                                                               |
| 3   | [What is TypeScript?](#what-is-typescript)                                                                                                                                                   |
| 4   | [Write a pictorial diagram of Angular architecture?](#write-a-pictorial-diagram-of-angular-architecture)                                                                                     |
| 5   | [What are the key components of Angular?](#what-are-the-key-components-of-angular)                                                                                                           |
| 6   | [What are directives?](#what-are-directives)                                                                                                                                                 |
| 7   | [What are components?](#what-are-components)                                                                                                                                                 |
| 8   | [What are the differences between Component and Directive?](#what-are-the-differences-between-component-and-directive)                                                                       |
| 9   | [What is a template?](#what-is-a-template)                                                                                                                                                   |
| 10  | [What is a module?](#what-is-a-module)                                                                                                                                                       |
| 11  | [What are lifecycle hooks available?](#what-are-lifecycle-hooks-available)                                                                                                                   |
| 12  | [What is a data binding?](#what-is-a-data-binding)                                                                                                                                           |
| 13  | [What is metadata?](#what-is-metadata)                                                                                                                                                       |
| 14  | [What is Angular CLI?](#what-is-angular-cli)                                                                                                                                                 |
| 15  | [What is the difference between constructor and ngOnInit?](#what-is-the-difference-between-constructor-and-ngoninit)                                                                         |
| 16  | [What is a service](#what-is-a-service)                                                                                                                                                      |
| 17  | [What is dependency injection in Angular?](#what-is-dependency-injection-in-angular)                                                                                                         |
| 18  | [How is Dependency Hierarchy formed?](#how-is-dependency-hierarchy-formed)                                                                                                                   |
| 19  | [What is the purpose of async pipe?](#what-is-the-purpose-of-async-pipe)                                                                                                                     |
| 20  | [What is the option to choose between inline and external template file?](#what-is-the-option-to-choose-between-inline-and-external-template-file)                                           |
| 21  | [What is the purpose of \*ngFor directive?](#what-is-the-purpose-of-ngfor-directive)                                                                                                         |
| 22  | [What is the purpose of ngIf directive?](#what-is-the-purpose-of-ngif-directive)                                                                                                             |
| 23  | [What happens if you use script tag inside template?](#what-happens-if-you-use-script-tag-inside-template)                                                                                   |
| 24  | [What is interpolation?](#what-is-interpolation)                                                                                                                                             |
| 25  | [What are template expressions?](#what-are-template-expressions)                                                                                                                             |
| 26  | [What are template statements?](#what-are-template-statements)                                                                                                                               |
| 27  | [How do you categorize data binding types?](#how-do-you-categorize-data-binding-types)                                                                                                       |
| 28  | [What are pipes?](#what-are-pipes)                                                                                                                                                           |
| 29  | [What is a parameterized pipe?](#what-is-a-parameterized-pipe)                                                                                                                               |
| 30  | [How do you chain pipes?](#how-do-you-chain-pipes)                                                                                                                                           |
| 31  | [What is a custom pipe?](#what-is-a-custom-pipe)                                                                                                                                             |
| 32  | [Give an example of custom pipe?](#give-an-example-of-custom-pipe)                                                                                                                           |
| 33  | [What is the difference between pure and impure pipe?](#what-is-the-difference-between-pure-and-impure-pipe)                                                                                 |
| 34  | [What is a bootstrapping module?](#what-is-a-bootstrapping-module)                                                                                                                           |
| 35  | [What are observables?](#what-are-observables)                                                                                                                                               |
| 36  | [What is HttpClient and its benefits?](#what-is-httpclient-and-its-benefits)                                                                                                                 |
| 37  | [Explain on how to use HttpClient with an example?](#explain-on-how-to-use-httpclient-with-an-example)                                                                                       |
| 38  | [How can you read full response?](#how-can-you-read-full-response)                                                                                                                           |
| 39  | [How do you perform Error handling?](#how-do-you-perform-error-handling)                                                                                                                     |
| 40  | [What is RxJS?](#what-is-rxjs)                                                                                                                                                               |
| 41  | [What is subscribing?](#what-is-subscribing)                                                                                                                                                 |
| 42  | [What is an observable?](#what-is-an-observable)                                                                                                                                             |
| 43  | [What is an observer?](#what-is-an-observer)                                                                                                                                                 |
| 44  | [What is the difference between promise and observable?](#what-is-the-difference-between-promise-and-observable)                                                                             |
| 45  | [What is multicasting?](#what-is-multicasting)                                                                                                                                               |
| 46  | [How do you perform error handling in observables?](#how-do-you-perform-error-handling-in-observables)                                                                                       |
| 47  | [What is the short hand notation for subscribe method?](#what-is-the-short-hand-notation-for-subscribe-method)                                                                               |
| 48  | [What are the utility functions provided by RxJS?](#what-are-the-utility-functions-provided-by-rxjs)                                                                                         |
| 49  | [What are observable creation functions?](#what-are-observable-creation-functions)                                                                                                           |
| 50  | [What will happen if you do not supply handler for observer?](#what-will-happen-if-you-do-not-supply-handler-for-observer)                                                                   |
| 51  | [What are angular elements?](#what-are-angular-elements)                                                                                                                                     |
| 52  | [What is the browser support of Angular Elements?](#what-is-the-browser-support-of-angular-elements)                                                                                         |
| 53  | [What are custom elements?](#what-are-custom-elements)                                                                                                                                       |
| 54  | [Do I need to bootstrap custom elements?](#do-i-need-to-bootstrap-custom-elements)                                                                                                           |
| 55  | [Explain how custom elements works internally?](#explain-how-custom-elements-works-internally)                                                                                               |
| 56  | [How to transfer components to custom elements?](#how-to-transfer-components-to-custom-elements)                                                                                             |
| 57  | [What are the mapping rules between Angular component and custom element?](#what-are-the-mapping-rules-between-angular-component-and-custom-element)                                         |
| 58  | [How do you define typings for custom elements?](#how-do-you-define-typings-for-custom-elements)                                                                                             |
| 59  | [What are dynamic components?](#what-are-dynamic-components)                                                                                                                                 |
| 60  | [What are the various kinds of directives?](#what-are-the-various-kinds-of-directives)                                                                                                       |
| 61  | [How do you create directives using CLI?](#how-do-you-create-directives-using-cli)                                                                                                           |
| 62  | [Give an example for attribute directives?](#give-an-example-for-attribute-directives)                                                                                                       |
| 63  | [What is Angular Router?](#what-is-angular-router)                                                                                                                                           |
| 64  | [What is the purpose of base href tag?](#what-is-the-purpose-of-base-href-tag)                                                                                                               |
| 65  | [What are the router imports?](#what-are-the-router-imports)                                                                                                                                 |
| 66  | [What is router outlet?](#what-is-router-outlet)                                                                                                                                             |
| 67  | [What are router links?](#what-are-router-links)                                                                                                                                             |
| 68  | [What are active router links?](#what-are-active-router-links)                                                                                                                               |
| 69  | [What is router state?](#what-is-router-state)                                                                                                                                               |
| 70  | [What are router events?](#what-are-router-events)                                                                                                                                           |
| 71  | [What is activated route?](#what-is-activated-route)                                                                                                                                         |
| 72  | [How do you define routes?](#how-do-you-define-routes)                                                                                                                                       |
| 73  | [What is the purpose of Wildcard route?](#what-is-the-purpose-of-wildcard-route)                                                                                                             |
| 74  | [Do I need a Routing Module always?](#do-i-need-a-routing-module-always)                                                                                                                     |
| 75  | [What is Angular Universal?](#what-is-angular-universal)                                                                                                                                     |
| 76  | [What are different types of compilation in Angular?](#what-are-different-types-of-compilation-in-angular)                                                                                   |
| 77  | [What is JIT?](#what-is-jit)                                                                                                                                                                 |
| 78  | [What is AOT?](#what-is-aot)                                                                                                                                                                 |
| 79  | [Why do we need compilation process?](#why-do-we-need-compilation-process)                                                                                                                   |
| 80  | [What are the advantages with AOT?](#what-are-the-advantages-with-aot)                                                                                                                       |
| 81  | [What are the ways to control AOT compilation?](#what-are-the-ways-to-control-aot-compilation)                                                                                               |
| 82  | [What are the restrictions of metadata?](#what-are-the-restrictions-of-metadata)                                                                                                             |
| 83  | [What are the two phases of AOT?](#what-are-the-two-phases-of-aot)                                                                                                                           |
| 84  | [Can I use arrow functions in AOT?](#can-i-use-arrow-functions-in-aot)                                                                                                                       |
| 85  | [What is the purpose of metadata json files?](#what-is-the-purpose-of-metadata-json-files)                                                                                                   |
| 86  | [Can I use any javascript feature for expression syntax in AOT?](#can-i-use-any-javascript-feature-for-expression-syntax-in-aot)                                                             |
| 87  | [What is folding?](#what-is-folding)                                                                                                                                                         |
| 88  | [What are macros?](#what-are-macros)                                                                                                                                                         |
| 89  | [Give an example of few metadata errors?](#give-an-example-of-few-metadata-errors)                                                                                                           |
| 90  | [What is metadata rewriting?](#what-is-metadata-rewriting)                                                                                                                                   |
| 91  | [How do you provide configuration inheritance?](#how-do-you-provide-configuration-inheritance)                                                                                               |
| 92  | [How do you specify angular template compiler options?](#how-do-you-specify-angular-template-compiler-options)                                                                               |
| 93  | [How do you enable binding expression validation?](#how-do-you-enable-binding-expression-validation)                                                                                         |
| 94  | [What is the purpose of any type cast function?](#what-is-the-purpose-of-any-type-cast-function)                                                                                             |
| 95  | [What is Non null type assertion operator?](#what-is-non-null-type-assertion-operator)                                                                                                       |
| 96  | [What is type narrowing?](#what-is-type-narrowing)                                                                                                                                           |
| 97  | [How do you describe various dependencies in angular application?](#how-do-you-describe-various-dependencies-in-angular-application)                                                         |
| 98  | [What is zone?](#what-is-zone)                                                                                                                                                               |
| 99  | [What is the purpose of common module?](#what-is-the-purpose-of-common-module)                                                                                                               |
| 100 | [What is codelyzer?](#what-is-codelyzer)                                                                                                                                                     |
| 101 | [What is angular animation?](#what-is-angular-animation)                                                                                                                                     |
| 102 | [What are the steps to use animation module?](#what-are-the-steps-to-use-animation-module)                                                                                                   |
| 103 | [What is State function?](#what-is-state-function)                                                                                                                                           |
| 104 | [What is Style function?](#what-is-style-function)                                                                                                                                           |
| 105 | [What is the purpose of animate function?](#what-is-the-purpose-of-animate-function)                                                                                                         |
| 106 | [What is transition function?](#what-is-transition-function)                                                                                                                                 |
| 107 | [How to inject the dynamic script in angular?](#how-to-inject-the-dynamic-script-in-angular)                                                                                                 |
| 108 | [What is a service worker and its role in Angular?](#what-is-a-service-worker-and-its-role-in-angular)                                                                                       |
| 109 | [What are the design goals of service workers?](#what-are-the-design-goals-of-service-workers)                                                                                               |
| 110 | [What are the differences between AngularJS and Angular with respect to dependency injection?](#what-are-the-differences-between-angularjs-and-angular-with-respect-to-dependency-injection) |
| 111 | [What is Angular Ivy?](#what-is-angular-ivy)                                                                                                                                                 |
| 112 | [What are the features included in ivy preview?](#what-are-the-features-included-in-ivy-preview)                                                                                             |
| 113 | [Can I use AOT compilation with Ivy?](#can-i-use-aot-compilation-with-ivy)                                                                                                                   |
| 114 | [What is Angular Language Service?](#what-is-angular-language-service)                                                                                                                       |
| 115 | [How do you install angular language service in the project?](#how-do-you-install-angular-language-service-in-the-project)                                                                   |
| 116 | [Is there any editor support for Angular Language Service?](#is-there-any-editor-support-for-angular-language-service)                                                                       |
| 117 | [Explain the features provided by Angular Language Service?](#explain-the-features-provided-by-angular-language-service)                                                                     |
| 118 | [How do you add web workers in your application?](#how-do-you-add-web-workers-in-your-application)                                                                                           |
| 119 | [What are the limitations with web workers?](#what-are-the-limitations-with-web-workers)                                                                                                     |
| 120 | [What is Angular CLI Builder?](#what-is-angular-cli-builder)                                                                                                                                 |
| 121 | [What is a builder?](#what-is-a-builder)                                                                                                                                                     |
| 122 | [How do you invoke a builder?](#how-do-you-invoke-a-builder)                                                                                                                                 |
| 123 | [How do you create app shell in Angular?](#how-do-you-create-app-shell-in-angular)                                                                                                           |
| 124 | [What are the case types in Angular?](#what-are-the-case-types-in-angular)                                                                                                                   |
| 125 | [What are the class decorators in Angular?](#what-are-the-class-decorators-in-angular)                                                                                                       |
| 126 | [What are class field decorators?](#what-are-class-field-decorators)                                                                                                                         |
| 127 | [What is declarable in Angular?](#what-is-declarable-in-angular)                                                                                                                             |
| 128 | [What are the restrictions on declarable classes?](#what-are-the-restrictions-on-declarable-classes)                                                                                         |
| 129 | [What is a DI token?](#what-is-a-di-token)                                                                                                                                                   |
| 130 | [What is Angular DSL?](#what-is-angular-dsl)                                                                                                                                                 |
| 131 | [What is an rxjs Subject?](#what-is-an-rxjs-Subject)                                                                                                                                         |
| 132 | [What is Bazel tool?](#what-is-bazel-tool)                                                                                                                                                   |
| 133 | [What are the advantages of Bazel tool?](#what-are-the-advantages-of-bazel-tool)                                                                                                             |
| 134 | [How do you use Bazel with Angular CLI?](#how-do-you-use-bazel-with-angular-cli)                                                                                                             |
| 135 | [How do you run Bazel directly?](#how-do-you-run-bazel-directly)                                                                                                                             |
| 136 | [What is platform in Angular?](#what-is-platform-in-angular)                                                                                                                                 |
| 137 | [What happens if I import the same module twice?](#what-happens-if-i-import-the-same-module-twice)                                                                                           |
| 138 | [How do you select an element with in a component template?](#how-do-you-select-an-element-with-in-a-component-template)                                                                     |
| 139 | [How do you detect route change in Angular?](#how-do-you-detect-route-change-in-angular)                                                                                                     |
| 140 | [How do you pass headers for HTTP client?](#how-do-you-pass-headers-for-http-client)                                                                                                         |
| 141 | [What is the purpose of differential loading in CLI?](#what-is-the-purpose-of-differential-loading-in-cli)                                                                                   |
| 142 | [Is Angular supports dynamic imports?](#is-angular-supports-dynamic-imports)                                                                                                                 |
| 143 | [What is lazy loading?](#what-is-lazy-loading)                                                                                                                                               |
| 144 | [What are workspace APIs?](#what-are-workspace-apis)                                                                                                                                         |
| 145 | [How do you upgrade angular version?](#how-do-you-upgrade-angular-version)                                                                                                                   |
| 146 | [What is Angular Material?](#what-is-angular-material)                                                                                                                                       |
| 147 | [How do you upgrade location service of angularjs?](#how-do-you-upgrade-location-service-of-angularjs)                                                                                       |
| 148 | [What is NgUpgrade?](#what-is-ngupgrade)                                                                                                                                                     |
| 149 | [How do you test Angular application using CLI?](#how-do-you-test-angular-application-using-cli)                                                                                             |
| 150 | [How to use polyfills in Angular application?](#how-to-use-polyfills-in-angular-application)                                                                                                 |
| 151 | [What are the ways to trigger change detection in Angular?](#what-are-the-ways-to-trigger-change-detection-in-angular)                                                                       |
| 152 | [What are the differences of various versions of Angular?](#what-are-the-differences-of-various-versions-of-angular)                                                                         |
| 153 | [What are the security principles in angular?](#what-are-the-security-principles-in-angular)                                                                                                 |
| 154 | [What is the reason to deprecate Web Tracing Framework?](#what-is-the-reason-to-deprecate-web-tracing-framework)                                                                             |
| 155 | [What is the reason to deprecate web worker packages?](#what-is-the-reason-to-deprecate-web-worker-packages)                                                                                 |
| 156 | [How do you find angular CLI version?](#how-do-you-find-angular-cli-version)                                                                                                                 |
| 157 | [What is the browser support for Angular?](#what-is-the-browser-support-for-angular)                                                                                                         |
| 158 | [What is schematic](#what-is-schematic)                                                                                                                                                      |
| 159 | [What is rule in Schematics?](#what-is-rule-in-schematics)                                                                                                                                   |
| 160 | [What is Schematics CLI?](#what-is-schematics-cli)                                                                                                                                           |

1. ### What is Angular Framework?

   Angular is a **TypeScript-based open-source** front-end platform that makes it easy to build applications with in web/mobile/desktop. The major features of this framework such as declarative templates, dependency injection, end to end tooling, and many more other features are used to ease the development.

   **[⬆ Back to Top](#table-of-contents)**

# Error Catalog

## Snyk Error Codes

The error codes in the table below describe the codes that you may encounter while working with the [Snyk API](../snyk-api-info/) or [CLI](../snyk-cli/). When errors are encountered using the API, they will also have an appropriate [HTTP status code](https://en.wikipedia.org/wiki/List\_of\_HTTP\_status\_codes). If you encounter errors without an error code, use the HTTP status code to determine the appropriate action.



## [Snyk](https://docs.snyk.io/introducing-snyk)

#### [SNYK-0001](error-catalog.md#snyk-0001)

**Too many requests**

The service has received too many requests and will be throttled.

**HTTP Status:** [429](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/429)

#### [SNYK-0002](error-catalog.md#snyk-0002)

**Not implemented**

The server either does not recognize the request method, or it lacks the ability to fulfil the request.

**HTTP Status:** [501](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/501)

#### [SNYK-0003](error-catalog.md#snyk-0003)

**Bad request**

The server cannot or will not process the request due to an apparent client error (e.g. malformed request syntax, size too large, invalid request message framing, or deceptive request routing).

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-0004](error-catalog.md#snyk-0004)

**Timeout error**

The server did not receive a timely response from the upstream server.

**HTTP Status:** [504](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/504)

#### [SNYK-0005](error-catalog.md#snyk-0005)

**Unauthorised error**

Authentication failed or has not been provided.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

#### [SNYK-9999](error-catalog.md#snyk-9999)

**Server error**

An unexpected server error was encountered.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)



## OpenAPI

#### [SNYK-OPENAPI-0001](error-catalog.md#snyk-openapi-0001)

**Bad request**

The server cannot process the request due to invalid or corrupt data. Review the request, then try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://docs.snyk.io/snyk-api-info/getting-started-using-snyk-rest-api](https://docs.snyk.io/snyk-api-info/getting-started-using-snyk-rest-api)

#### [SNYK-OPENAPI-0002](error-catalog.md#snyk-openapi-0002)

**Forbidden**

Access to the requested resource is forbidden.

**HTTP Status:** [403](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/403)

#### [SNYK-OPENAPI-0003](error-catalog.md#snyk-openapi-0003)

**Not acceptable**

The server cannot provide a response that matches the provided accept headers. Review the request, then try again.

**HTTP Status:** [406](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/406)

#### [SNYK-OPENAPI-0004](error-catalog.md#snyk-openapi-0004)

**Not found**

The server cannot find the requested resource.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OPENAPI-0005](error-catalog.md#snyk-openapi-0005)

**Method not allowed**

The target endpoint does not support your request method. Review the request, then try again.

**HTTP Status:** [405](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/405)

#### [SNYK-OPENAPI-0006](error-catalog.md#snyk-openapi-0006)

**Request entity too large**

The request entity exceeds server limitations.

**HTTP Status:** [413](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/413)

#### [SNYK-OPENAPI-0007](error-catalog.md#snyk-openapi-0007)

**Unauthorized**

The request lacks authentication credentials for the requested resource.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

**Help Links:**

* [https://docs.snyk.io/snyk-api-info/authentication-for-api](https://docs.snyk.io/snyk-api-info/authentication-for-api)

#### [SNYK-OPENAPI-0008](error-catalog.md#snyk-openapi-0008)

**Unsupported media type**

The media format of the request is not supported.

**HTTP Status:** [415](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/415)



## [Open Source Languages & Package Managers](https://docs.snyk.io/products/snyk-open-source/language-and-package-manager-support)

#### [SNYK-OS-0001](error-catalog.md#snyk-os-0001)

**Unsupported Ecosystem**

The language or package manager is not supported.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://docs.snyk.io/products/snyk-open-source/language-and-package-manager-support](https://docs.snyk.io/products/snyk-open-source/language-and-package-manager-support)

#### [SNYK-OS-0002](error-catalog.md#snyk-os-0002)

**Unable to parse manifest file**

The provided manifest file could not be parsed as it has invalid syntax or does not match the expected schema. Review the manifest file, then try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-0003](error-catalog.md#snyk-os-0003)

**Lock file out of sync with manifest file**

Some of the dependencies that are expected to be in the lock file are missing, usually indicating that the lock file is out of sync with the provided manifest file. Re-sync the lock file, then try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-0004](error-catalog.md#snyk-os-0004)

**Unable to parse lock file**

The provided lock file could not be parsed as it has invalid syntax or does not match the expected schema. Review the lock file, then try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-0005](error-catalog.md#snyk-os-0005)

**Unknown dependency version**

Dependency version could not be resolved.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

**Help Links:**

* [https://support.snyk.io/hc/en-us/articles/360001373178-Could-not-determine-version-for-dependencies](https://support.snyk.io/hc/en-us/articles/360001373178-Could-not-determine-version-for-dependencies)

#### [SNYK-OS-0006](error-catalog.md#snyk-os-0006)

**Payload missing required elements**

The server could not process the request.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-0007](error-catalog.md#snyk-os-0007)

**Files cannot be processed**

The dependency service could not process the files.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-0008](error-catalog.md#snyk-os-0008)

**Source is not supported**

The source used is not supported by fetcher. The supported sources are: github, bitbucket, gitlab.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-0009](error-catalog.md#snyk-os-0009)

**Cannot get file from source**

Could not get the file from the source URL.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OS-0010](error-catalog.md#snyk-os-0010)

**No released version for versions range**

There was no version released for the specified versions range.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-0011](error-catalog.md#snyk-os-0011)

**Timeout when processing the dependency tree**

There was an timeout when processing the dependecy tree.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-DOTNET-0001](error-catalog.md#snyk-os-dotnet-0001)

**Unsupported manifest file type for remediation**

The provided manifest file is not supported by Snyk for .NET.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#git-services-for-.net-projects](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#git-services-for-.net-projects)
* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#dependencies-managed-by-packagereference](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#dependencies-managed-by-packagereference)
* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#dependencies-managed-by-packages.config](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#dependencies-managed-by-packages.config)
* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#paket-dependencies-managed-by-paket](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net#paket-dependencies-managed-by-paket)

#### [SNYK-OS-GO-0001](error-catalog.md#snyk-os-go-0001)

**Failed to access private module**

Snyk could not access the private modules within your go.mod files.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-snyk-cli](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-snyk-cli)
* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-git](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-git)

#### [SNYK-OS-GO-0002](error-catalog.md#snyk-os-go-0002)

**Go mod file not found**

A go.mod file was not found in the current directory or any parent directory.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-snyk-cli](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-snyk-cli)
* [https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-git](https://docs.snyk.io/scan-application-code/snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-golang#go-modules-and-git)

#### [SNYK-OS-GO-0003](error-catalog.md#snyk-os-go-0003)

**OAuth re-authorization required**

Your code is cloned on an isolated environment using Git as it is required by Snyk to analyze its dependencies.

Your Organization has enabled or enforced SAML SSO after you authorized Snyk to access your code, and a re-authentication is therefore required.

The error you're seeing is usually reproducible by attempting to do a `git clone` of your repository with incorrectly configured credentials. Verify your authentication configuration with your Git cloud provider and try again.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

**Help Links:**

* [https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/about-authentication-with-saml-single-sign-on#about-oauth-apps-github-apps-and-saml-sso](https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/about-authentication-with-saml-single-sign-on#about-oauth-apps-github-apps-and-saml-sso)

#### [SNYK-OS-GO-0004](error-catalog.md#snyk-os-go-0004)

**Your project repository is missing required files**

Generating the dependency graph requires Snyk to run go list `go list -deps -json` inside the Project. If the operation fails, creating a full dependency graph cannot continue.

This error usually means that you need some cleanup, such as `go mod tidy`) or your Project deployment process contains a code generation step such as `protobuf` or something similar that is not currently supported by Snyk.

To verify if this is the case, clone your Project in a clean environment, run go list `go list -deps -json` and verify whether the operation fails.

If Snyk cannot process your code successfully, insert the Snyk CLI as part of your deployment pipeline.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

**Help Links:**

* [https://docs.snyk.io/snyk-cli](https://docs.snyk.io/snyk-cli)
* [https://github.com/snyk/snyk-go-plugin](https://github.com/snyk/snyk-go-plugin)
* [https://github.com/golang/go/blob/master/src/cmd/go/internal/list/list.go](https://github.com/golang/go/blob/master/src/cmd/go/internal/list/list.go)

#### [SNYK-OS-MAVEN-0001](error-catalog.md#snyk-os-maven-0001)

**Missing property**

The required property is missing from the pom object.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0002](error-catalog.md#snyk-os-maven-0002)

**Unable to resolve value for property**

The targeted property could not be resolved with a valid value.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0003](error-catalog.md#snyk-os-maven-0003)

**Unable to resolve version for property**

The targeted property could not be resolved with a valid version.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0004](error-catalog.md#snyk-os-maven-0004)

**Cyclic property detected in POM file**

There is circular dependency among properties in the Maven project's configuration file (POM), preventing proper resolution and causing an error.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0005](error-catalog.md#snyk-os-maven-0005)

**Error parsing the XML file**

There is an error parsing the XML file. This could be referring to either pom.xml or maven-metadata.xml.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OS-MAVEN-0006](error-catalog.md#snyk-os-maven-0006)

**Invalid coordinates provided**

The coordinates provided for a project were invalid.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0007](error-catalog.md#snyk-os-maven-0007)

**Skipping group**

Skipping a specific groupId starting due to remapped coordinates.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0008](error-catalog.md#snyk-os-maven-0008)

**Pom file not found**

The pom file was not found in Maven repository.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0009](error-catalog.md#snyk-os-maven-0009)

**Missing project from POM**

A project element is missing from POM.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0010](error-catalog.md#snyk-os-maven-0010)

**Cannot resolve the target POM from the input XML**

Cannot resolve the targeted POM from the input XML.

**HTTP Status:** [422](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

#### [SNYK-OS-MAVEN-0011](error-catalog.md#snyk-os-maven-0011)

**Cannot resolve the target POM from the repository**

Cannot resolve the targeted POM from the repository.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-MAVEN-0012](error-catalog.md#snyk-os-maven-0012)

**Cannot get the build file repository**

Cannot get the build file repository.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-MAVEN-0013](error-catalog.md#snyk-os-maven-0013)

**Unable to create hosted git info**

Cannot create source URL.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)



## Builds

#### [SNYK-OS-8001](error-catalog.md#snyk-os-8001)

**Invalid request**

The provided request payload is not valid for the selected ecosystem. Please review the API documentation.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://apidocs.snyk.io/](https://apidocs.snyk.io/)

#### [SNYK-OS-8002](error-catalog.md#snyk-os-8002)

**Build environment not found**

The build environment for the provided context could not be found. Please ensure you have created the build environment first.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)



## SbomExport

#### [SNYK-OS-9000](error-catalog.md#snyk-os-9000)

**SBOM generation export server error**

An unexpected error occurred during the SBOM generation. Review the request, then try again. If the error persists, contact Snyk Support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OS-9001](error-catalog.md#snyk-os-9001)

**Dependency graph error**

An unexpected dependency graph error occurred. Review the request, then try again. If the error persists, contact Snyk Support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OS-9002](error-catalog.md#snyk-os-9002)

**Error parsing dependency graph**

The dependency graph cannot be parsed due to an unexpected error. Review the request, then try again. If the error persists, contact Snyk Support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OS-9003](error-catalog.md#snyk-os-9003)

**SBOM not supported due to project type**

Only SBOMs for Snyk Open Source or Snyk Container projects are supported.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-9004](error-catalog.md#snyk-os-9004)

**SBOM not supported**

Only SBOMs for open source projects are supported (Snyk Open Source).

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-9005](error-catalog.md#snyk-os-9005)

**Dependency graph request cannot be processed**

The server cannot process the request due to incomplete data. Review the request, then try again.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-9006](error-catalog.md#snyk-os-9006)

**Authorization failed due to missing API token**

The API token is misconfigured or expired. Configure or generate the API token, then try again.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

**Help Links:**

* [https://docs.snyk.io/snyk-api-info/revoking-and-regenerating-snyk-api-tokens](https://docs.snyk.io/snyk-api-info/revoking-and-regenerating-snyk-api-tokens)

#### [SNYK-OS-9007](error-catalog.md#snyk-os-9007)

**Client request cannot be processed**

The body of the request is empty. Review the request, then try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-9008](error-catalog.md#snyk-os-9008)

**Invalid dependency graph**

The request cannot be processed due to an internal error. Review the request, then try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)



## Workspaces

#### [SNYK-OS-9101](error-catalog.md#snyk-os-9101)

**Unauthorized Credentials**

The credentials that have been provided could not be authorized with the upstream service.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

#### [SNYK-OS-9102](error-catalog.md#snyk-os-9102)

**Insufficient Privileges**

The access token that has been provided has insufficient privileges to complete the requested operation with the upstream service.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

#### [SNYK-OS-9103](error-catalog.md#snyk-os-9103)

**Invalid Credentials**

The credentials provided do to match the expected format.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-9104](error-catalog.md#snyk-os-9104)

**Invalid Token**

The workspace token provided is invalid.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-9105](error-catalog.md#snyk-os-9105)

**Missing Access Token**

The request is missing the access token.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

#### [SNYK-OS-9106](error-catalog.md#snyk-os-9106)

**Unauthorized Request**

The provided token could not be authorized.

**HTTP Status:** [401](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

#### [SNYK-OS-9201](error-catalog.md#snyk-os-9201)

**Target Not Found**

The requested target could not be found. Please ensure the target details are correct.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-9202](error-catalog.md#snyk-os-9202)

**Invalid Target**

The target information that has been provided is in an invalid format.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-9301](error-catalog.md#snyk-os-9301)

**File Size Error**

The requested file is too large to be transferred.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OS-9302](error-catalog.md#snyk-os-9302)

**File Not Found**

The requested file could not be found. Please ensure the file path exists in the provided target.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OS-9901](error-catalog.md#snyk-os-9901)

**Too Many Requests**

The upstream service has received too many requests and will be throttled.

**HTTP Status:** [429](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/429)

#### [SNYK-OS-9902](error-catalog.md#snyk-os-9902)

**Service Unavailable**

The upstream service is unavailable.

**HTTP Status:** [502](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/502)



## [Open Source Unmanaged](https://docs.snyk.io/snyk-cli/test-for-vulnerabilities/scan-all-unmanaged-jar-files)

#### [SNYK-OSJVM-001](error-catalog.md#snyk-osjvm-001)

**Maven Search Service Unavailable**

The upstream Maven search service is not available.

**HTTP Status:** [503](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/503)

**Help Links:**

* [https://search.maven.org](https://search.maven.org)
* [https://status.maven.org](https://status.maven.org)

#### [SNYK-OSJVM-002](error-catalog.md#snyk-osjvm-002)

**SHA1 Not Found**

Unable to find the coordinates for the provided SHA1.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

**Help Links:**

* [https://docs.snyk.io/snyk-cli/test-for-vulnerabilities/scan-all-unmanaged-jar-files](https://docs.snyk.io/snyk-cli/test-for-vulnerabilities/scan-all-unmanaged-jar-files)



## [PURL Vulnerabilities](https://docs.snyk.io/introducing-snyk/getting-started-snyk-intel-vuln-db-access#about-the-snyk-vulnerability-database)

#### [SNYK-OSSI-1040](error-catalog.md#snyk-ossi-1040)

**Your organisation is not authorised to perform this action**

You likely don’t have access to the Beta. To get access, you can request access to the Beta through your account manager or team.

**HTTP Status:** [403](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/403)

#### [SNYK-OSSI-1050](error-catalog.md#snyk-ossi-1050)

**Authorization request failure**

Unexpected error when authenticating. Please try again, and if you continue to experience issues please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-2010](error-catalog.md#snyk-ossi-2010)

**Invalid PURL has been provided**

Please make sure that the purl you’ve provided is valid. Please see the Package URL specification link for further information.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://github.com/package-url/purl-spec/blob/master/PURL-SPECIFICATION.rst](https://github.com/package-url/purl-spec/blob/master/PURL-SPECIFICATION.rst)

#### [SNYK-OSSI-2011](error-catalog.md#snyk-ossi-2011)

**Ensure you specify a namespace in the purl and then try again**

You have requested a package type which requires a namespace (eg. maven group id). Please supply the namespace in order to retrieve the package correctly.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

**Help Links:**

* [https://github.com/package-url/purl-spec/blob/master/PURL-SPECIFICATION.rst](https://github.com/package-url/purl-spec/blob/master/PURL-SPECIFICATION.rst)

#### [SNYK-OSSI-2020](error-catalog.md#snyk-ossi-2020)

**Ecosystem is not supported**

Ensure that the package type is a supported type.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2021](error-catalog.md#snyk-ossi-2021)

**Purl components required**

Currently we require a list of components of the package url specification. The purl supplied by the user did not specify all the components which we currently require.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2022](error-catalog.md#snyk-ossi-2022)

**You have submitted a purl with components which are not supported**

Please remove the component which is not supported, and try to make the request again. The endpoint only accepts particular components.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2030](error-catalog.md#snyk-ossi-2030)

**Requested package not found**

The package you’ve specified in the purl can not be found in our vulnerability database. Please check that the package name, ecosystem and version are correct and then try again.

**HTTP Status:** [404](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

#### [SNYK-OSSI-2031](error-catalog.md#snyk-ossi-2031)

**Vulnerability service is currently not available**

This issue is unexpected, and the service should recover quickly. If not, please contact support.

**HTTP Status:** [503](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/503)

#### [SNYK-OSSI-2032](error-catalog.md#snyk-ossi-2032)

**This issue is unexpected and the service should recover quickly if not please contact support**

An unexpected error occurred. Please try again, and if you continue to experience issues please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-2033](error-catalog.md#snyk-ossi-2033)

**This issue is unexpected and the service should recover quickly if not please contact support**

An unexpected error occurred with the vulnerability service. Please try again, and if you continue to experience issues please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-2040](error-catalog.md#snyk-ossi-2040)

**An error was experienced by the service when processing the request**

This issue is unexpected, and the service should recover quickly. If not, please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-2041](error-catalog.md#snyk-ossi-2041)

**Invalid pagination parameters**

Please ensure the supplied pagination limit is > 1 and <= 1000, and that the offset is >= 0.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2042](error-catalog.md#snyk-ossi-2042)

**Purls provided exceeds limit**

The number of purls sent in the request exceeds the limit set by the service.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2043](error-catalog.md#snyk-ossi-2043)

**Number of issues exceeds limit**

The number of issues found for the provided purls exceeds the limit defined by the API. You may attempt to resolve this by reducing the number of purls you send in a single request.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2044](error-catalog.md#snyk-ossi-2044)

**Expected distro to be present**

The given Package URL does not have a required distro qualifier.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2045](error-catalog.md#snyk-ossi-2045)

**Unsupported Debian distro**

This Debian distro is not currently supported.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2046](error-catalog.md#snyk-ossi-2046)

**Expected namespace to be present**

The given Package URL does not have a required namespace.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-2047](error-catalog.md#snyk-ossi-2047)

**Vendor not supported**

The given Package URL does not contain a supported vendor.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)



## OpenSourceProjectIssues

#### [SNYK-OSSI-OSPI-1001](error-catalog.md#snyk-ossi-ospi-1001)

**Invalid request**

Please check the body of your request and try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-OSPI-1002](error-catalog.md#snyk-ossi-ospi-1002)

**Unable to return valid API response**

This should resolve, however please contact support if you continue to experience issues.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-OSPI-2001](error-catalog.md#snyk-ossi-ospi-2001)

**Failed to process data**

This should resolve, however please contact support if you continue to experience issues.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-OSPI-3001](error-catalog.md#snyk-ossi-ospi-3001)

**Failed to store issue data**

Please check your inputs and try again. If you continue to experience issues please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-OSPI-4001](error-catalog.md#snyk-ossi-ospi-4001)

**Internal server error**

This issue is unexpected, and the service should recover quickly. If not, please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)



## Open Source Project Snapshots

#### [SNYK-OSSI-OSPSS-1001](error-catalog.md#snyk-ossi-ospss-1001)

**Invalid request**

Please check the body of your request and try again.

**HTTP Status:** [400](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

#### [SNYK-OSSI-OSPSS-1002](error-catalog.md#snyk-ossi-ospss-1002)

**Unable to return valid API response**

This should resolve, however please contact support if you continue to experience issues.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-OSPSS-2001](error-catalog.md#snyk-ossi-ospss-2001)

**Failed to process data**

This should resolve, however please contact support if you continue to experience issues.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-OSPSS-3001](error-catalog.md#snyk-ossi-ospss-3001)

**Failed to store snapshot data**

Please check your inputs and try again. If you continue to experience issues please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

#### [SNYK-OSSI-OSPSS-4001](error-catalog.md#snyk-ossi-ospss-4001)

**Internal server error**

This issue is unexpected, and the service should recover quickly. If not, please contact support.

**HTTP Status:** [500](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

\--- Generated at 2023-06-26T14:30:05.817Z

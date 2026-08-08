Description
Helium positions itself as a browser based on ungoogled-chromium. However, there is a key discrepancy regarding extension management on specific Google domains. In standard Chromium-based browsers, all user extensions are forcibly disabled by the browser's internal logic whenever a user visits the Chrome Web Store. In a true ungoogled-chromium build, this restriction is completely stripped out, and extensions continue to function normally. Currently, Helium still exhibits the standard Chromium behavior.

Additionally, even the built-in uBlock Origin extension gets completely disabled on the Chrome Web Store pages. This defeats the purpose of having a privacy-focused browser out of the box, as users are left entirely unprotected on these domains.

If Helium were truly built on ungoogled-chromium, it should have inherited this exact patch: extensions should remain fully functional on all pages, including the Chrome Web Store, ensuring complete decoupling from Google's hardcoded constraints.

The creators of the Helium browser are insulting their users' intelligence by stripping away functionality as if treating adults like small children under the guise of security. In reality, they took standard Chromium and lied about the browser being built on Ungoogled-chromium, as the Helium browser inherited all of Chromium's built-in limitations.

# cross-river-postman
Cross River Postman collection

## Cross River Postman Collection

To make development easier, we’ve put together a [**Postman collection**](https://www.postman.com/cross-river/cross-river-apis/overview) with pre-built requests for all the Cross River [**APIs intro**](docId\:sfnHqbapK4Sg6QBZw9P8y). Use this collection to explore, test, and build your integration directly in Postman with minimal extra coding and setup required.To immediately fork our collection, click

:::Iframe{iframeHeight="0" code="<div class=&#x22;postman-run-button&#x22;&#xA;data-postman-action=&#x22;collection/fork&#x22;&#xA;data-postman-visibility=&#x22;public&#x22;&#xA;data-postman-var-1=&#x22;47019181-21421164-5987-44e5-b242-84890920c4a0&#x22;&#xA;data-postman-collection-url=&#x22;entityId=47019181-21421164-5987-44e5-b242-84890920c4a0&entityType=collection&workspaceId=31a0ddbd-695b-483b-869b-211c7ed79cf3&#x22;&#xA;data-postman-param=&#x22;env%5BCross%20River%20Sandbox%5D=W3sia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiJZb3VyIGNsaWVudCBpZCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IllvdXIgY2xpZW50IGlkIGhlcmUiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IllvdXIgY2xpZW50IGlkIGhlcmUiLCJzZXNzaW9uSW5kZXgiOjB9LHsia2V5IjoiY2xpZW50X3NlY3JldCIsInZhbHVlIjoiWW91IGNsaWVudCBzZWNyZXQgaGVyZSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJzZWNyZXQiLCJzZXNzaW9uVmFsdWUiOiJZb3UgY2xpZW50IHNlY3JldCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3UgY2xpZW50IHNlY3JldCBoZXJlIiwic2Vzc2lvbkluZGV4IjoxfSx7ImtleSI6InRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjJ9LHsia2V5IjoicGFydG5lcl9pZCIsInZhbHVlIjoiWW91ciBwYXJ0bmVyIGlkIGhlcmUiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IllvdXIgcGFydG5lciBpZCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3VyIHBhcnRuZXIgaWQgaGVyZSIsInNlc3Npb25JbmRleCI6M30seyJrZXkiOiJwcm9kdWN0X2lkIiwidmFsdWUiOiJZb3VyIHByb2R1Y3QgaWQgaGVyZSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiWW91ciBwcm9kdWN0IGlkIGhlcmUiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IllvdXIgcHJvZHVjdCBpZCBoZXJlIiwic2Vzc2lvbkluZGV4Ijo0fSx7ImtleSI6ImNvbmZpZ3VyYXRpb25faWQiLCJ2YWx1ZSI6IllvdXIgY29uZmlndXJhdGlvbiBpZCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJZb3VyIGNvbmZpZ3VyYXRpb24gaWQgaGVyZSIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiWW91ciBjb25maWd1cmF0aW9uIGlkIGhlcmUiLCJzZXNzaW9uSW5kZXgiOjV9LHsia2V5IjoiY2FsbGJhY2tfdXJsIiwidmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwic2Vzc2lvbkluZGV4Ijo2fSx7ImtleSI6InB0cGVfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiYWNjb3VudF9udW1iZXIiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjh9LHsia2V5Ijoic3NuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4Ijo5fSx7ImtleSI6InBheW1lbnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjEwfSx7ImtleSI6ImN1c3RvbWVyX2lkX2J1c2luZXNzIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxMX0seyJrZXkiOiJjdXN0b21lcl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTJ9LHsia2V5IjoiY2FyZFRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxM30seyJrZXkiOiJNQ19jYXJkVG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjE0fSx7ImtleSI6InJlZ2lzdHJhdGlvbl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTV9LHsia2V5IjoiUFRQRV9jbGllbnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTZ9LHsia2V5IjoiUFRQRV9jbGllbnRfc2VjcmV0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjE3fSx7ImtleSI6InJlcXVlc3RJZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxOH0seyJrZXkiOiJhbW91bnQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTl9LHsia2V5Ijoic291cmNlU2VuZGVyTmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoyMH1d&#x22;></div>&#xA;<script type=&#x22;text/javascript&#x22;>&#xA;  (function (p,o,s,t,m,a,n) {&#xA;    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });&#xA;    !o.getElementById(s+t) && o.getElementsByTagName(&#x22;head&#x22;)[0].appendChild((&#xA;      (n = o.createElement(&#x22;script&#x22;)),&#xA;      (n.id = s+t), (n.async = 1), (n.src = m), n&#xA;    ));&#xA;  }(window, document, &#x22;_pm&#x22;, &#x22;PostmanRunObject&#x22;, &#x22;https://run.pstmn.io/button.js&#x22;));&#xA;</script>"}

:::

Just complete the [**Postman collection**](docId\:Fb95IuTT_D2JMljOJPHHb) setup details, and start making calls in Sandbox through [**Postman**](https://www.postman.com/downloads/).&#x20;

## Access (bearer) token

We've created our Postman developer sandbox environment to provide a safe space to test the Cross River APIs. In the Cross River Postman collection, you perform authentication using a bearer token.&#x20;

To get the IDs you need to set up the access (bearer) token required to run the collection:

1. [**Get API credentials**](docId\:Z-MVwOV-p00-xX082NabK): With these credentials you request and receive an access token to use for sending APIs in our sandbox environment
2. [**Get access token**](docId\:kP_8xNEZDhnaTwYlGXt22): Once you receive your API credentials and before you can use our APIs, you get an access token using the `client_id` and `client_secret` you received when you registered.&#x20;

## Fork Cross River collection

Head straight to our [**Postman workspace**](https://www.postman.com/cross-river/cross-river-apis/overview) to fork our collection.&#x20;

:::hint{type="warning"}
Once forked, don’t forget to set your environment variables for sandbox.
:::

## Configure your Postman environment

To use the collection you just created, navigate to it, click **Environments,** and select **Sandbox**. Copy your Cross River client ID and client secret, and paste them into the `client_Id` and `client_secret` fields.   For Card Payments, paste them into the `ptpe_client_id` and `ptpe_client_secret` fields. &#x20;

Now you’re ready obtain a token and begin to send requests.&#x20;

1. Run `Authorization/Obtain token` to generate your token. For Card Payments, run `Card Payments/Authorization/Get P2PE token`.
2. The variable `{{token}}` (or `ptpe_token` for Card Payments) is added automatically to your environment by a post reponse script.  When the token expires you need to follow step 1 again.
3. There are several variables that you might need to populate depending on which endpoint you're exercising.  For example, `partner_id`, `product_id`, `configuration_id `and `callback_url`.
4. There are also some variables that are populated through scripts, such as `token` and `ptpe_token` that should not be populated manually.

## Ping the sandbox

Run a simple test to verify that you can connect to the Cross River sandbox.

To send a Ping request, in Postman open *Collections > Cross River API Collection > Authorization* and run the **Ping** endpoint.

## Modify requests

To update a request, make your changes on the **Body** tab. Values in double curly brackets pull from your environment variables. Check our [**APIs intro**](docId\:sfnHqbapK4Sg6QBZw9P8y) to see which fields each endpoint accepts, and view requests in your preferred language.

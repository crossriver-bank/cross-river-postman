# cross-river-postman
Cross River Postman collection



To make development easier, we’ve put together a Postman collection with pre-built requests for all the Cross River API endpoints
. Use this collection to explore, test, and build your integration directly in Postman with minimal extra coding and setup required.To immediately fork our collection, click




  (function (p,o,s,t,m,a,n) {
    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });
    !o.getElementById(s+t) && o.getElementsByTagName("head")[0].appendChild((
      (n = o.createElement("script")),
      (n.id = s+t), (n.async = 1), (n.src = m), n
    ));
  }(window, document, "_pm", "PostmanRunObject", "https://run.pstmn.io/button.js"));

1<div class="postman-run-button"
2data-postman-action="collection/fork"
3data-postman-visibility="public"
4data-postman-var-1="47019181-21421164-5987-44e5-b242-84890920c4a0"
5data-postman-collection-url="entityId=47019181-21421164-5987-44e5-b242-84890920c4a0&entityType=collection&workspaceId=31a0ddbd-695b-483b-869b-211c7ed79cf3"
6data-postman-param="env%5BCross%20River%20Sandbox%5D=W3sia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiJZb3VyIGNsaWVudCBpZCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IllvdXIgY2xpZW50IGlkIGhlcmUiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IllvdXIgY2xpZW50IGlkIGhlcmUiLCJzZXNzaW9uSW5kZXgiOjB9LHsia2V5IjoiY2xpZW50X3NlY3JldCIsInZhbHVlIjoiWW91IGNsaWVudCBzZWNyZXQgaGVyZSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJzZWNyZXQiLCJzZXNzaW9uVmFsdWUiOiJZb3UgY2xpZW50IHNlY3JldCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3UgY2xpZW50IHNlY3JldCBoZXJlIiwic2Vzc2lvbkluZGV4IjoxfSx7ImtleSI6InRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjJ9LHsia2V5IjoicGFydG5lcl9pZCIsInZhbHVlIjoiWW91ciBwYXJ0bmVyIGlkIGhlcmUiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IllvdXIgcGFydG5lciBpZCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3VyIHBhcnRuZXIgaWQgaGVyZSIsInNlc3Npb25JbmRleCI6M30seyJrZXkiOiJwcm9kdWN0X2lkIiwidmFsdWUiOiJZb3VyIHByb2R1Y3QgaWQgaGVyZSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiWW91ciBwcm9kdWN0IGlkIGhlcmUiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IllvdXIgcHJvZHVjdCBpZCBoZXJlIiwic2Vzc2lvbkluZGV4Ijo0fSx7ImtleSI6ImNvbmZpZ3VyYXRpb25faWQiLCJ2YWx1ZSI6IllvdXIgY29uZmlndXJhdGlvbiBpZCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJZb3VyIGNvbmZpZ3VyYXRpb24gaWQgaGVyZSIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiWW91ciBjb25maWd1cmF0aW9uIGlkIGhlcmUiLCJzZXNzaW9uSW5kZXgiOjV9LHsia2V5IjoiY2FsbGJhY2tfdXJsIiwidmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwic2Vzc2lvbkluZGV4Ijo2fSx7ImtleSI6InB0cGVfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiYWNjb3VudF9udW1iZXIiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjh9LHsia2V5Ijoic3NuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4Ijo5fSx7ImtleSI6InBheW1lbnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjEwfSx7ImtleSI6ImN1c3RvbWVyX2lkX2J1c2luZXNzIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxMX0seyJrZXkiOiJjdXN0b21lcl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTJ9LHsia2V5IjoiY2FyZFRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxM30seyJrZXkiOiJNQ19jYXJkVG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjE0fSx7ImtleSI6InJlZ2lzdHJhdGlvbl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTV9LHsia2V5IjoiUFRQRV9jbGllbnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTZ9LHsia2V5IjoiUFRQRV9jbGllbnRfc2VjcmV0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjE3fSx7ImtleSI6InJlcXVlc3RJZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxOH0seyJrZXkiOiJhbW91bnQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTl9LHsia2V5Ijoic291cmNlU2VuZGVyTmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoyMH1d"></div>
7<script type="text/javascript">
8  (function (p,o,s,t,m,a,n) {
9    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });
10    !o.getElementById(s+t) && o.getElementsByTagName("head")[0].appendChild((
11      (n = o.createElement("script")),
12      (n.id = s+t), (n.async = 1), (n.src = m), n
13    ));
14  }(window, document, "_pm", "PostmanRunObject", "https://run.pstmn.io/button.js"));
15</script>

<div class="postman-run-button"
data-postman-action="collection/fork"
data-postman-visibility="public"
data-postman-var-1="47019181-21421164-5987-44e5-b242-84890920c4a0"
data-postman-collection-url="entityId=47019181-21421164-5987-44e5-b242-84890920c4a0&entityType=collection&workspaceId=31a0ddbd-695b-483b-869b-211c7ed79cf3"
data-postman-param="env%5BCross%20River%20Sandbox%5D=W3sia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiJZb3VyIGNsaWVudCBpZCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IllvdXIgY2xpZW50IGlkIGhlcmUiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IllvdXIgY2xpZW50IGlkIGhlcmUiLCJzZXNzaW9uSW5kZXgiOjB9LHsia2V5IjoiY2xpZW50X3NlY3JldCIsInZhbHVlIjoiWW91IGNsaWVudCBzZWNyZXQgaGVyZSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJzZWNyZXQiLCJzZXNzaW9uVmFsdWUiOiJZb3UgY2xpZW50IHNlY3JldCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3UgY2xpZW50IHNlY3JldCBoZXJlIiwic2Vzc2lvbkluZGV4IjoxfSx7ImtleSI6InRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjJ9LHsia2V5IjoicGFydG5lcl9pZCIsInZhbHVlIjoiWW91ciBwYXJ0bmVyIGlkIGhlcmUiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IllvdXIgcGFydG5lciBpZCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3VyIHBhcnRuZXIgaWQgaGVyZSIsInNlc3Npb25JbmRleCI6M30seyJrZXkiOiJwcm9kdWN0X2lkIiwidmFsdWUiOiJZb3VyIHByb2R1Y3QgaWQgaGVyZSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiWW91ciBwcm9kdWN0IGlkIGhlcmUiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IllvdXIgcHJvZHVjdCBpZCBoZXJlIiwic2Vzc2lvbkluZGV4Ijo0fSx7ImtleSI6ImNvbmZpZ3VyYXRpb25faWQiLCJ2YWx1ZSI6IllvdXIgY29uZmlndXJhdGlvbiBpZCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJZb3VyIGNvbmZpZ3VyYXRpb24gaWQgaGVyZSIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiWW91ciBjb25maWd1cmF0aW9uIGlkIGhlcmUiLCJzZXNzaW9uSW5kZXgiOjV9LHsia2V5IjoiY2FsbGJhY2tfdXJsIiwidmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiJZb3VyIGNhbGxiYWNrIFVSTCBoZXJlIiwic2Vzc2lvbkluZGV4Ijo2fSx7ImtleSI6InB0cGVfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiYWNjb3VudF9udW1iZXIiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjh9LHsia2V5Ijoic3NuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4Ijo5fSx7ImtleSI6InBheW1lbnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjEwfSx7ImtleSI6ImN1c3RvbWVyX2lkX2J1c2luZXNzIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxMX0seyJrZXkiOiJjdXN0b21lcl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTJ9LHsia2V5IjoiY2FyZFRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxM30seyJrZXkiOiJNQ19jYXJkVG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjE0fSx7ImtleSI6InJlZ2lzdHJhdGlvbl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTV9LHsia2V5IjoiUFRQRV9jbGllbnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTZ9LHsia2V5IjoiUFRQRV9jbGllbnRfc2VjcmV0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiIiwiY29tcGxldGVTZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjE3fSx7ImtleSI6InJlcXVlc3RJZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxOH0seyJrZXkiOiJhbW91bnQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiIiLCJjb21wbGV0ZVNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6MTl9LHsia2V5Ijoic291cmNlU2VuZGVyTmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IiIsImNvbXBsZXRlU2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoyMH1d"></div>
<script type="text/javascript">
  (function (p,o,s,t,m,a,n) {
    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });
    !o.getElementById(s+t) && o.getElementsByTagName("head")[0].appendChild((
      (n = o.createElement("script")),
      (n.id = s+t), (n.async = 1), (n.src = m), n
    ));
  }(window, document, "_pm", "PostmanRunObject", "https://run.pstmn.io/button.js"));
</script>

/**
 * Reset the text fill color so that placeholder is visible
 */
.npm__react-simple-code-editor__textarea:empty {
  -webkit-text-fill-color: inherit !important;
}

/**
 * Hack to apply on some CSS on IE10 and IE11
 */
@media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
  /**
    * IE doesn't support '-webkit-text-fill-color'
    * So we use 'color: transparent' to make the text transparent on IE
    * Unlike other browsers, it doesn't affect caret color in IE
    */
  .npm__react-simple-code-editor__textarea {
    color: transparent !important;
  }

  .npm__react-simple-code-editor__textarea::selection {
    background-color: #accef7 !important;
    color: transparent !important;
  }
}






Just complete the Postman collection
 setup details, and start making calls in Sandbox through Postman. 



Access (bearer) token



We've created our Postman developer sandbox environment to provide a safe space to test the Cross River APIs. In the Cross River Postman collection, you perform authentication using a bearer token. 


To get the IDs you need to set up the access (bearer) token required to run the collection:


Get API credentials
: With these credentials you request and receive an access token to use for sending APIs in our sandbox environment



Get access token
: Once you receive your API credentials and before you can use our APIs, you get an access token using the client_id and client_secret you received when you registered. 




Fork Cross River collection



Head straight to our Postman workspace to fork our collection. 




Once forked, don’t forget to set your environment variables for sandbox.





Configure your Postman environment



To use the collection you just created, navigate to it, click Environments, and select Sandbox. Copy your Cross River client ID and client secret, and paste them into the client_Id and client_secret fields.   For Card Payments, paste them into the ptpe_client_id and ptpe_client_secret fields.  


Now you’re ready obtain a token and begin to send requests. 


Run Authorization/Obtain token to generate your token. For Card Payments, run Card Payments/Authorization/Get P2PE token.



The variable {{token}} (or ptpe_token for Card Payments) is added automatically to your environment by a post reponse script.  When the token expires you need to follow step 1 again.



There are several variables that you might need to populate depending on which endpoint you're exercising.  For example, partner_id, product_id, configuration_id and callback_url.



There are also some variables that are populated through scripts, such as token and ptpe_token that should not be populated manually.




Ping the sandbox



Run a simple test to verify that you can connect to the Cross River sandbox.


To send a Ping request, in Postman open Collections > Cross River API Collection > Authorization and run the Ping endpoint.



Modify requests



To update a request, make your changes on the Body tab. Values in double curly brackets pull from your environment variables. Check our API docs
 to see which fields each endpoint accepts, and view requests in your preferred language.



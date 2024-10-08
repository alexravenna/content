---
title: Content-Length
slug: Web/HTTP/Headers/Content-Length
page-type: http-header
browser-compat: http.headers.Content-Length
---

{{HTTPSidebar}}

The **`Content-Length`** header indicates the size of the message body, in bytes, sent to the recipient.

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Header type</th>
      <td>
        {{Glossary("Request header")}},
        {{Glossary("Response header")}},
        {{Glossary("Content header")}}
      </td>
    </tr>
    <tr>
      <th scope="row">{{Glossary("Forbidden header name")}}</th>
      <td>yes</td>
    </tr>
    <tr>
      <th scope="row">
        {{Glossary("CORS-safelisted response header")}}
      </th>
      <td>yes</td>
    </tr>
  </tbody>
</table>

## Syntax

```http
Content-Length: <length>
```

## Directives

- \<length>
  - : The length in octets.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{HTTPHeader("Transfer-Encoding")}}

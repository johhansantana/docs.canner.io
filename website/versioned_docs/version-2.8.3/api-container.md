---
id: version-2.8.3-api-container
title: Container
sidebar_label: Container
original_id: api-container
---

## Properties

<table>
  <tr>
    <th>Name</th>
    <th>Type</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>schema</td>
    <td width="30%">
      <code>
        <a href="api-types#loadedschema">
          LoadedSchema
        </a>
      </code>
    </td>
    <td>
      <b>canner-schema-loader</b> will compile your schema (<b>canner-script</b>) into a JSON object.
    </td>
  </tr>
  <tr>
    <td>sidebarConfig</td>
    <td>
      <code>
        <a href="api-types#menuconfig">MenuConfig</a> | boolean
      </code>
    </td>
    <td>
      The configuration of the sidebar, if the value is <code>true</code>, it will generate the default sidebar.
    </td>
  </tr>
  <tr>
    <td>navbarConfig</td>
    <td>
      <code>
        <a href="api-types#navbarconfig">NavbarConfig</a>
      </code>
    </td>
    <td>
      The configuration of the navbar.
    </td>
  </tr>
  <tr>
    <td>router</td>
    <td>
      <code>
        <a href="api-types#router">
          Router
        </a>
      </code>
    </td>
    <td>
      Controlling the routing and provides methods to get url parameter.
    </td>
  </tr>
  <tr>
    <td>dataDidChange</td>
    <td>
      <code>
        <a href="api-types#changeddata">ChangedData</a> => void
      </code>
    </td>
    <td>
      The callback when data change, same as the <code>dataDidChange</code> in properties of <code><a href="api-canner#properties">canner</a></code>.
    </td>
  </tr>
</table>
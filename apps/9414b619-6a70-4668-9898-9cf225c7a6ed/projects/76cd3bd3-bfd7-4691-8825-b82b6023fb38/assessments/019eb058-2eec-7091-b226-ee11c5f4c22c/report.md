# ZavaAccountManager

> Consolidated assessment across all units detected under this component root. Each unit's full report is inlined below; raw per-unit artefacts (report JSON, facts, scenarios) remain in their subfolders.

## Units

| Unit |
|------|
| [ZavaAccountManager](#zavaaccountmanager) |

## ZavaAccountManager

### ZavaAccountManager (.NET)


#### Summary

| Metric | Value |
|--------|-------|
| Total Issues | 5 |
| Mandatory Blockers | 0 |
| Potential Issues | 3 |

#### Component Information

| Property | Value |
|----------|-------|
| Language | C# |
| Frameworks | .NETFramework,Version=v4.8 |
| Build tools | MSBuild |

#### Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Access to external resources via HTTP is detected | Potential | 3 | [4](#Access_to_external_resources_via_HTTP_is_detected) |
| Hardcoded URLs detected | Potential | 1 | [4](#Hardcoded_URLs_detected) |
| SQL database connection detected | Potential | 3 | [1](#SQL_database_connection_detected) |
| System.Data.SqlClient dependency detected | Optional | 3 | [33](#System_Data_SqlClient_dependency_detected) |
| Connection strings without configuration builders detected | Optional | 3 | [2](#Connection_strings_without_configuration_builders_detected) |

##### Issue Details

<details id="Access_to_external_resources_via_HTTP_is_detected">
<summary><b>Access to external resources via HTTP is detected</b> — affected files</summary>

- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 4301)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 4316)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5031)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5046)`

</details>

<details id="Hardcoded_URLs_detected">
<summary><b>Hardcoded URLs detected</b> — affected files</summary>

- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 4386)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5116)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Login.aspx.cs (line 0, col 472)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Logout.aspx.cs (line 0, col 306)`

</details>

<details id="SQL_database_connection_detected">
<summary><b>SQL database connection detected</b> — affected files</summary>

- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\web.config`

</details>

<details id="System_Data_SqlClient_dependency_detected">
<summary><b>System.Data.SqlClient dependency detected</b> — affected files</summary>

- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3156)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3166)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 4020)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 4030)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 6101)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 6111)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3597)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3607)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 2179)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 2189)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3326)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3336)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3800)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3810)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 2924)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 2934)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5807)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5817)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 1185)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 1195)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 2280)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 2292)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3427)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3439)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3901)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3913)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3025)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 3037)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5908)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 5920)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 1286)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\Default.aspx.cs (line 0, col 1298)`
- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\web.config`

</details>

<details id="Connection_strings_without_configuration_builders_detected">
<summary><b>Connection strings without configuration builders detected</b> — affected files</summary>

- `modernize-cc-assess\019eb058-2eec-7091-b226-ee11c5f4c22c\repos\ZavaAccountManager\web.config`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)




---
title: "FhirStore"
block_external_search_index: true
---

A FhirStore is a datastore inside a Healthcare dataset that conforms to the FHIR (https://www.hl7.org/fhir/STU3/)
standard for Healthcare information exchange

To get more information about FhirStore, see:

* [API documentation](https://cloud.google.com/healthcare/docs/reference/rest/v1beta1/projects.locations.datasets.fhirStores)
* How-to Guides
    * [Creating a FHIR store](https://cloud.google.com/healthcare/docs/how-tos/fhir)

> This content is derived from https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/healthcare_fhir_store.html.markdown.



## Create a FhirStore Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/healthcare/#FhirStore">FhirStore</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/healthcare/#FhirStoreArgs">FhirStoreArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">FhirStore</span><span class="p">(resource_name, opts=None, </span>dataset=None<span class="p">, </span>disable_referential_integrity=None<span class="p">, </span>disable_resource_versioning=None<span class="p">, </span>enable_history_import=None<span class="p">, </span>enable_update_create=None<span class="p">, </span>labels=None<span class="p">, </span>name=None<span class="p">, </span>notification_config=None<span class="p">, </span>version=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewFhirStore<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/healthcare?tab=doc#FhirStoreArgs">FhirStoreArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/healthcare?tab=doc#FhirStore">FhirStore</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Healthcare.FhirStore.html">FhirStore</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Healthcare.Inputs.FhirStoreArgs.html">FhirStoreArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Fhir<wbr>Store<wbr>Notification<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">*Fhir<wbr>Store<wbr>Notification<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Fhir<wbr>Store<wbr>Notification<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable_<wbr>referential_<wbr>integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable_<wbr>resource_<wbr>versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>history_<wbr>import</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>update_<wbr>create</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Dict[Fhir<wbr>Store<wbr>Notification<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## FhirStore Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Fhir<wbr>Store<wbr>Notification<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">*Fhir<wbr>Store<wbr>Notification<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Fhir<wbr>Store<wbr>Notification<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>disable_<wbr>referential_<wbr>integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>disable_<wbr>resource_<wbr>versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable_<wbr>history_<wbr>import</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable_<wbr>update_<wbr>create</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>notification_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Dict[Fhir<wbr>Store<wbr>Notification<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>self_<wbr>link</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing FhirStore Resource

Get an existing FhirStore resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">pulumi.Input&lt;pulumi.ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/healthcare/#FhirStoreState">FhirStoreState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/healthcare/#FhirStore">FhirStore</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>dataset=None<span class="p">, </span>disable_referential_integrity=None<span class="p">, </span>disable_resource_versioning=None<span class="p">, </span>enable_history_import=None<span class="p">, </span>enable_update_create=None<span class="p">, </span>labels=None<span class="p">, </span>name=None<span class="p">, </span>notification_config=None<span class="p">, </span>self_link=None<span class="p">, </span>version=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetFhirStore<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">pulumi.IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/healthcare?tab=doc#FhirStoreState">FhirStoreState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/healthcare?tab=doc#FhirStore">FhirStore</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Healthcare.FhirStore.html">FhirStore</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Pulumi.Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Healthcare.FhirStoreState.html">FhirStoreState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Fhir<wbr>Store<wbr>Notification<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">*Fhir<wbr>Store<wbr>Notification<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable<wbr>Referential<wbr>Integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable<wbr>Resource<wbr>Versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>History<wbr>Import</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Update<wbr>Create</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Fhir<wbr>Store<wbr>Notification<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>dataset</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Identifies the dataset addressed by this request. Must be in the format
'projects/{project}/locations/{location}/datasets/{dataset}'
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable_<wbr>referential_<wbr>integrity</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable referential integrity in this FHIR store. This field is immutable after FHIR store creation. The
default value is false, meaning that the API will enforce referential integrity and fail the requests that will result
in inconsistent state in the FHIR store. When this field is set to true, the API will skip referential integrity check.
Consequently, operations that rely on references, such as Patient.get$everything, will not return all the results if
broken references exist. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disable_<wbr>resource_<wbr>versioning</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to disable resource versioning for this FHIR store. This field can not be changed after the creation of FHIR
store. If set to false, which is the default behavior, all write operations will cause historical versions to be
recorded automatically. The historical versions can be fetched through the history APIs, but cannot be updated. If set
to true, no historical versions will be kept. The server will send back errors for attempts to read the historical
versions. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>history_<wbr>import</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to allow the bulk import API to accept history bundles and directly insert historical resource versions into the
FHIR store. Importing resource histories creates resource interactions that appear to have occurred in the past, which
clients may not want to allow. If set to false, history bundles within an import will fail with an error. ** Changing
this property may recreate the FHIR store (removing all data) ** ** This property can be changed manually in the Google
Cloud Healthcare admin console without recreating the FHIR store **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>update_<wbr>create</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether this FHIR store has the updateCreate capability. This determines if the client can use an Update operation to
create a new resource with a client-specified ID. If false, all IDs are server-assigned through the Create operation and
attempts to Update a non-existent resource will return errors. Please treat the audit logs with appropriate levels of
care if client-specified resource IDs contain sensitive data such as patient identifiers, those IDs will be part of the
FHIR resource path recorded in Cloud audit logs and Cloud Pub/Sub notifications.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}User-supplied key-value pairs used to organize FHIR stores. Label keys must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}][\p{Ll}\p{Lo}\p{N}_-]{0,62} Label values are optional, must be between 1 and 63 characters long, have a
UTF-8 encoding of maximum 128 bytes, and must conform to the following PCRE regular expression:
[\p{Ll}\p{Lo}\p{N}_-]{0,63} No more than 64 labels can be associated with a given store. An object containing a list of
"key": value pairs. Example: { "name": "wrench", "mass": "1.3kg", "count": "3" }.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The resource name for the FhirStore. ** Changing this property may recreate the FHIR store (removing all data) **
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#fhirstorenotificationconfig">Dict[Fhir<wbr>Store<wbr>Notification<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}A nested object resource
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>self_<wbr>link</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The fully qualified name of this dataset
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The FHIR specification version. Supported values include DSTU2, STU3 and R4. Defaults to STU3.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Fhir<wbr>Store<wbr>Notification<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#FhirStoreNotificationConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#FhirStoreNotificationConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/healthcare?tab=doc#FhirStoreNotificationConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/healthcare?tab=doc#FhirStoreNotificationConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Pubsub<wbr>Topic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Pubsub<wbr>Topic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>pubsub<wbr>Topic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>pubsub<wbr>Topic</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}








---
title: "Account"
block_external_search_index: true
---

Manages an Azure Storage Account.

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/storage_account.html.markdown.



## Create a Account Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/storage/#Account">Account</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/storage/#AccountArgs">AccountArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">Account</span><span class="p">(resource_name, opts=None, </span>access_tier=None<span class="p">, </span>account_kind=None<span class="p">, </span>account_replication_type=None<span class="p">, </span>account_tier=None<span class="p">, </span>blob_properties=None<span class="p">, </span>custom_domain=None<span class="p">, </span>enable_https_traffic_only=None<span class="p">, </span>identity=None<span class="p">, </span>is_hns_enabled=None<span class="p">, </span>location=None<span class="p">, </span>name=None<span class="p">, </span>network_rules=None<span class="p">, </span>queue_properties=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>static_website=None<span class="p">, </span>tags=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewAccount<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountArgs">AccountArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#Account">Account</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Storage.Account.html">Account</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Storage.Inputs.AccountArgs.html">AccountArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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

    <dt class="property-optional"
            title="Optional">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Account<wbr>Custom<wbr>Domain<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Account<wbr>Static<wbr>Website<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">*Account<wbr>Blob<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">*Account<wbr>Custom<wbr>Domain</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">*Account<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">*Account<wbr>Network<wbr>Rules<wbr>Type</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">*Account<wbr>Queue<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">*Account<wbr>Static<wbr>Website</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties?</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Account<wbr>Custom<wbr>Domain?</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity?</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules?</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties?</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Account<wbr>Static<wbr>Website?</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>access_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account_<wbr>kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>account_<wbr>replication_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>account_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>blob_<wbr>properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Dict[Account<wbr>Blob<wbr>Properties]</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>custom_<wbr>domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Dict[Account<wbr>Custom<wbr>Domain]</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>https_<wbr>traffic_<wbr>only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Dict[Account<wbr>Identity]</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is_<wbr>hns_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network_<wbr>rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Dict[Account<wbr>Network<wbr>Rules]</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>queue_<wbr>properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Dict[Account<wbr>Queue<wbr>Properties]</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>static_<wbr>website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Dict[Account<wbr>Static<wbr>Website]</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## Account Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Account<wbr>Custom<wbr>Domain?</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Account<wbr>Static<wbr>Website?</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">*Account<wbr>Custom<wbr>Domain</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules<wbr>Type</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">*Account<wbr>Static<wbr>Website</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Account<wbr>Custom<wbr>Domain?</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Account<wbr>Static<wbr>Website?</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>access_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account_<wbr>kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account_<wbr>replication_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>blob_<wbr>properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Dict[Account<wbr>Blob<wbr>Properties]</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>custom_<wbr>domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Dict[Account<wbr>Custom<wbr>Domain]</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable_<wbr>https_<wbr>traffic_<wbr>only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Dict[Account<wbr>Identity]</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>is_<wbr>hns_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>network_<wbr>rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Dict[Account<wbr>Network<wbr>Rules]</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>access_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>blob_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>blob_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>blob_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>dfs_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>dfs_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>file_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>file_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>queue_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>queue_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>table_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>table_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>web_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>web_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>queue_<wbr>properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Dict[Account<wbr>Queue<wbr>Properties]</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>access_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>blob_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>blob_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>blob_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>dfs_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>dfs_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>file_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>file_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>queue_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>queue_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>table_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>table_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>web_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>web_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>static_<wbr>website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Dict[Account<wbr>Static<wbr>Website]</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing Account Resource

Get an existing Account resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">pulumi.Input&lt;pulumi.ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/storage/#AccountState">AccountState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/storage/#Account">Account</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>access_tier=None<span class="p">, </span>account_kind=None<span class="p">, </span>account_replication_type=None<span class="p">, </span>account_tier=None<span class="p">, </span>blob_properties=None<span class="p">, </span>custom_domain=None<span class="p">, </span>enable_https_traffic_only=None<span class="p">, </span>identity=None<span class="p">, </span>is_hns_enabled=None<span class="p">, </span>location=None<span class="p">, </span>name=None<span class="p">, </span>network_rules=None<span class="p">, </span>primary_access_key=None<span class="p">, </span>primary_blob_connection_string=None<span class="p">, </span>primary_blob_endpoint=None<span class="p">, </span>primary_blob_host=None<span class="p">, </span>primary_connection_string=None<span class="p">, </span>primary_dfs_endpoint=None<span class="p">, </span>primary_dfs_host=None<span class="p">, </span>primary_file_endpoint=None<span class="p">, </span>primary_file_host=None<span class="p">, </span>primary_location=None<span class="p">, </span>primary_queue_endpoint=None<span class="p">, </span>primary_queue_host=None<span class="p">, </span>primary_table_endpoint=None<span class="p">, </span>primary_table_host=None<span class="p">, </span>primary_web_endpoint=None<span class="p">, </span>primary_web_host=None<span class="p">, </span>queue_properties=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>secondary_access_key=None<span class="p">, </span>secondary_blob_connection_string=None<span class="p">, </span>secondary_blob_endpoint=None<span class="p">, </span>secondary_blob_host=None<span class="p">, </span>secondary_connection_string=None<span class="p">, </span>secondary_dfs_endpoint=None<span class="p">, </span>secondary_dfs_host=None<span class="p">, </span>secondary_file_endpoint=None<span class="p">, </span>secondary_file_host=None<span class="p">, </span>secondary_location=None<span class="p">, </span>secondary_queue_endpoint=None<span class="p">, </span>secondary_queue_host=None<span class="p">, </span>secondary_table_endpoint=None<span class="p">, </span>secondary_table_host=None<span class="p">, </span>secondary_web_endpoint=None<span class="p">, </span>secondary_web_host=None<span class="p">, </span>static_website=None<span class="p">, </span>tags=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetAccount<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">pulumi.IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountState">AccountState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#Account">Account</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Storage.Account.html">Account</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Pulumi.Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Storage.AccountState.html">AccountState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Account<wbr>Custom<wbr>Domain<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Account<wbr>Static<wbr>Website<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">*Account<wbr>Blob<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">*Account<wbr>Custom<wbr>Domain</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">*Account<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">*Account<wbr>Network<wbr>Rules<wbr>Type</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">*Account<wbr>Queue<wbr>Properties</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">*Account<wbr>Static<wbr>Website</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>blob<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Account<wbr>Blob<wbr>Properties?</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>custom<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Account<wbr>Custom<wbr>Domain?</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Account<wbr>Identity?</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Account<wbr>Network<wbr>Rules?</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>queue<wbr>Properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Account<wbr>Queue<wbr>Properties?</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>static<wbr>Website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Account<wbr>Static<wbr>Website?</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>access_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the access tier for `BlobStorage`, `FileStorage` and `StorageV2` accounts. Valid options are `Hot` and `Cool`, defaults to `Hot`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account_<wbr>kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the Kind of account. Valid options are `BlobStorage`, `BlockBlobStorage`, `FileStorage`, `Storage` and `StorageV2`. Changing this forces a new resource to be created. Defaults to `StorageV2`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account_<wbr>replication_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the type of replication to use for this storage account. Valid options are `LRS`, `GRS`, `RAGRS` and `ZRS`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>account_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Defines the Tier to use for this storage account. Valid options are `Standard` and `Premium`. For `FileStorage` accounts only `Premium` is valid. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>blob_<wbr>properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobproperties">Dict[Account<wbr>Blob<wbr>Properties]</a></span>
    </dt>
    <dd>{{% md %}}A `blob_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>custom_<wbr>domain</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountcustomdomain">Dict[Account<wbr>Custom<wbr>Domain]</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>https_<wbr>traffic_<wbr>only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Boolean flag which forces HTTPS if enabled, see [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information. Defaults to `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountidentity">Dict[Account<wbr>Identity]</a></span>
    </dt>
    <dd>{{% md %}}A `identity` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is_<wbr>hns_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled? This can be used with Azure Data Lake Storage Gen 2 ([see here for more information](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account/)). Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the storage account. Changing this forces a new resource to be created. This must be unique across the entire Azure service, not just within the resource group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network_<wbr>rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountnetworkrules">Dict[Account<wbr>Network<wbr>Rules]</a></span>
    </dt>
    <dd>{{% md %}}A `network_rules` block as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>access_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The primary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>blob_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>blob_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>blob_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>dfs_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>dfs_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>file_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>file_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The primary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>queue_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>queue_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>table_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>table_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>web_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>primary_<wbr>web_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>queue_<wbr>properties</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueueproperties">Dict[Account<wbr>Queue<wbr>Properties]</a></span>
    </dt>
    <dd>{{% md %}}A `queue_properties` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource group in which to create the storage account. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>access_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>blob_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>blob_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>blob_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>dfs_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>dfs_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>file_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>file_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The secondary location of the storage account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>queue_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>queue_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>table_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>table_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>web_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary_<wbr>web_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>static_<wbr>website</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountstaticwebsite">Dict[Account<wbr>Static<wbr>Website]</a></span>
    </dt>
    <dd>{{% md %}}A `static_website` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Account<wbr>Blob<wbr>Properties</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountBlobProperties">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountBlobProperties">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountBlobPropertiesArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountBlobPropertiesOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiescorsrule">List&lt;Account<wbr>Blob<wbr>Properties<wbr>Cors<wbr>Rule<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Delete<wbr>Retention<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiesdeleteretentionpolicy">Account<wbr>Blob<wbr>Properties<wbr>Delete<wbr>Retention<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `delete_retention_policy` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiescorsrule">[]Account<wbr>Blob<wbr>Properties<wbr>Cors<wbr>Rule</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Delete<wbr>Retention<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiesdeleteretentionpolicy">*Account<wbr>Blob<wbr>Properties<wbr>Delete<wbr>Retention<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A `delete_retention_policy` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiescorsrule">Account<wbr>Blob<wbr>Properties<wbr>Cors<wbr>Rule[]?</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>delete<wbr>Retention<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiesdeleteretentionpolicy">Account<wbr>Blob<wbr>Properties<wbr>Delete<wbr>Retention<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}A `delete_retention_policy` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiescorsrule">List[Account<wbr>Blob<wbr>Properties<wbr>Cors<wbr>Rule]</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>delete<wbr>Retention<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountblobpropertiesdeleteretentionpolicy">Dict[Account<wbr>Blob<wbr>Properties<wbr>Delete<wbr>Retention<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A `delete_retention_policy` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Blob<wbr>Properties<wbr>Cors<wbr>Rule</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountBlobPropertiesCorsRule">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountBlobPropertiesCorsRule">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountBlobPropertiesCorsRuleArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountBlobPropertiesCorsRuleOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Blob<wbr>Properties<wbr>Delete<wbr>Retention<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountBlobPropertiesDeleteRetentionPolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountBlobPropertiesDeleteRetentionPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountBlobPropertiesDeleteRetentionPolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountBlobPropertiesDeleteRetentionPolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that the blob should be retained, between `1` and `365` days. Defaults to `7`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that the blob should be retained, between `1` and `365` days. Defaults to `7`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>days</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that the blob should be retained, between `1` and `365` days. Defaults to `7`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>days</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that the blob should be retained, between `1` and `365` days. Defaults to `7`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Custom<wbr>Domain</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountCustomDomain">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountCustomDomain">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountCustomDomainArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountCustomDomainOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name to use for the Storage Account, which will be validated by Azure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Use<wbr>Subdomain</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should the Custom Domain Name be validated by using indirect CNAME validation?
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name to use for the Storage Account, which will be validated by Azure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Use<wbr>Subdomain</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should the Custom Domain Name be validated by using indirect CNAME validation?
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name to use for the Storage Account, which will be validated by Azure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>use<wbr>Subdomain</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should the Custom Domain Name be validated by using indirect CNAME validation?
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name to use for the Storage Account, which will be validated by Azure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>use<wbr>Subdomain</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should the Custom Domain Name be validated by using indirect CNAME validation?
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Identity</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountIdentity">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountIdentity">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountIdentityArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountIdentityOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Principal<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Principal ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tenant<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Tenant ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the identity type of the Storage Account. At this time the only allowed value is `SystemAssigned`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Principal<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Principal ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tenant<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Tenant ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the identity type of the Storage Account. At this time the only allowed value is `SystemAssigned`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>principal<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Principal ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tenant<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Tenant ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the identity type of the Storage Account. At this time the only allowed value is `SystemAssigned`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>principal_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Principal ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tenant_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Tenant ID for the Service Principal associated with the Identity of this Storage Account.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the identity type of the Storage Account. At this time the only allowed value is `SystemAssigned`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Network<wbr>Rules</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountNetworkRules">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountNetworkRules">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountNetworkRulesTypeArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountNetworkRulesTypeOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Bypasses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Specifies whether traffic is bypassed for Logging/Metrics/AzureServices. Valid options are
any combination of `Logging`, `Metrics`, `AzureServices`, or `None`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the default action of allow or deny when no other rules match. Valid options are `Deny` or `Allow`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of public IP or IP ranges in CIDR Format. Only IPV4 addresses are allowed. Private IP address ranges (as defined in [RFC 1918](https://tools.ietf.org/html/rfc1918#section-3)) are not allowed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Virtual<wbr>Network<wbr>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of resource ids for subnets.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Bypasses</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Specifies whether traffic is bypassed for Logging/Metrics/AzureServices. Valid options are
any combination of `Logging`, `Metrics`, `AzureServices`, or `None`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the default action of allow or deny when no other rules match. Valid options are `Deny` or `Allow`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of public IP or IP ranges in CIDR Format. Only IPV4 addresses are allowed. Private IP address ranges (as defined in [RFC 1918](https://tools.ietf.org/html/rfc1918#section-3)) are not allowed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Virtual<wbr>Network<wbr>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of resource ids for subnets.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>bypasses</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Specifies whether traffic is bypassed for Logging/Metrics/AzureServices. Valid options are
any combination of `Logging`, `Metrics`, `AzureServices`, or `None`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the default action of allow or deny when no other rules match. Valid options are `Deny` or `Allow`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of public IP or IP ranges in CIDR Format. Only IPV4 addresses are allowed. Private IP address ranges (as defined in [RFC 1918](https://tools.ietf.org/html/rfc1918#section-3)) are not allowed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>virtual<wbr>Network<wbr>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of resource ids for subnets.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>bypasses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Specifies whether traffic is bypassed for Logging/Metrics/AzureServices. Valid options are
any combination of `Logging`, `Metrics`, `AzureServices`, or `None`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>default_<wbr>action</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the default action of allow or deny when no other rules match. Valid options are `Deny` or `Allow`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>rules</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of public IP or IP ranges in CIDR Format. Only IPV4 addresses are allowed. Private IP address ranges (as defined in [RFC 1918](https://tools.ietf.org/html/rfc1918#section-3)) are not allowed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>virtual_<wbr>network_<wbr>subnet_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of resource ids for subnets.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Queue<wbr>Properties</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountQueueProperties">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountQueueProperties">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiescorsrule">List&lt;Account<wbr>Queue<wbr>Properties<wbr>Cors<wbr>Rule<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hour<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieshourmetrics">Account<wbr>Queue<wbr>Properties<wbr>Hour<wbr>Metrics<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `hour_metrics` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Logging</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieslogging">Account<wbr>Queue<wbr>Properties<wbr>Logging<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `logging` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Minute<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiesminutemetrics">Account<wbr>Queue<wbr>Properties<wbr>Minute<wbr>Metrics<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `minute_metrics` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiescorsrule">[]Account<wbr>Queue<wbr>Properties<wbr>Cors<wbr>Rule</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hour<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieshourmetrics">*Account<wbr>Queue<wbr>Properties<wbr>Hour<wbr>Metrics</a></span>
    </dt>
    <dd>{{% md %}}A `hour_metrics` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Logging</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieslogging">*Account<wbr>Queue<wbr>Properties<wbr>Logging</a></span>
    </dt>
    <dd>{{% md %}}A `logging` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Minute<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiesminutemetrics">*Account<wbr>Queue<wbr>Properties<wbr>Minute<wbr>Metrics</a></span>
    </dt>
    <dd>{{% md %}}A `minute_metrics` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiescorsrule">Account<wbr>Queue<wbr>Properties<wbr>Cors<wbr>Rule[]?</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hour<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieshourmetrics">Account<wbr>Queue<wbr>Properties<wbr>Hour<wbr>Metrics?</a></span>
    </dt>
    <dd>{{% md %}}A `hour_metrics` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>logging</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieslogging">Account<wbr>Queue<wbr>Properties<wbr>Logging?</a></span>
    </dt>
    <dd>{{% md %}}A `logging` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>minute<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiesminutemetrics">Account<wbr>Queue<wbr>Properties<wbr>Minute<wbr>Metrics?</a></span>
    </dt>
    <dd>{{% md %}}A `minute_metrics` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cors<wbr>Rules</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiescorsrule">List[Account<wbr>Queue<wbr>Properties<wbr>Cors<wbr>Rule]</a></span>
    </dt>
    <dd>{{% md %}}A `cors_rule` block as defined above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hour<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieshourmetrics">Dict[Account<wbr>Queue<wbr>Properties<wbr>Hour<wbr>Metrics]</a></span>
    </dt>
    <dd>{{% md %}}A `hour_metrics` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>logging</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertieslogging">Dict[Account<wbr>Queue<wbr>Properties<wbr>Logging]</a></span>
    </dt>
    <dd>{{% md %}}A `logging` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>minute<wbr>Metrics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#accountqueuepropertiesminutemetrics">Dict[Account<wbr>Queue<wbr>Properties<wbr>Minute<wbr>Metrics]</a></span>
    </dt>
    <dd>{{% md %}}A `minute_metrics` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Queue<wbr>Properties<wbr>Cors<wbr>Rule</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountQueuePropertiesCorsRule">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountQueuePropertiesCorsRule">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesCorsRuleArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesCorsRuleOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of headers that are allowed to be a part of the cross-origin request.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Methods</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of http headers that are allowed to be executed by the origin. Valid options are
`DELETE`, `GET`, `HEAD`, `MERGE`, `POST`, `OPTIONS` or `PUT`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>allowed<wbr>Origins</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of origin domains that will be allowed by CORS.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>exposed<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of response headers that are exposed to CORS clients.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>max<wbr>Age<wbr>In<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The number of seconds the client should cache a preflight response.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Queue<wbr>Properties<wbr>Hour<wbr>Metrics</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountQueuePropertiesHourMetrics">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountQueuePropertiesHourMetrics">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesHourMetricsArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesHourMetricsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether hour metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether hour metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Indicates whether hour metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether hour metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Queue<wbr>Properties<wbr>Logging</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountQueuePropertiesLogging">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountQueuePropertiesLogging">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesLoggingArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesLoggingOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Delete</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all delete requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Read</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all read requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Write</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all write requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Delete</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all delete requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Read</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all read requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Write</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all write requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>delete</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Indicates whether all delete requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>read</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Indicates whether all read requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>write</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Indicates whether all write requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>delete</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all delete requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>read</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all read requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>write</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether all write requests should be logged. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Queue<wbr>Properties<wbr>Minute<wbr>Metrics</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountQueuePropertiesMinuteMetrics">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountQueuePropertiesMinuteMetrics">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesMinuteMetricsArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountQueuePropertiesMinuteMetricsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether minute metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether minute metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Indicates whether minute metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether minute metrics are enabled for the Queue service. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>include<wbr>Apis</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether metrics should generate summary statistics for called API operations.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>retention<wbr>Policy<wbr>Days</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Specifies the number of days that logs will be retained. Changing this forces a new resource.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The version of storage analytics to configure. Changing this forces a new resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Account<wbr>Static<wbr>Website</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#AccountStaticWebsite">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#AccountStaticWebsite">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountStaticWebsiteArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#AccountStaticWebsiteOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Error404Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The absolute path to a custom webpage that should be used when a request is made which does not correspond to an existing file.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Index<wbr>Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The webpage that Azure Storage serves for requests to the root of a website or any subfolder. For example, index.html. The value is case-sensitive.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Error404Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The absolute path to a custom webpage that should be used when a request is made which does not correspond to an existing file.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Index<wbr>Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The webpage that Azure Storage serves for requests to the root of a website or any subfolder. For example, index.html. The value is case-sensitive.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>error404Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The absolute path to a custom webpage that should be used when a request is made which does not correspond to an existing file.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>index<wbr>Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The webpage that Azure Storage serves for requests to the root of a website or any subfolder. For example, index.html. The value is case-sensitive.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>error404Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The absolute path to a custom webpage that should be used when a request is made which does not correspond to an existing file.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>index<wbr>Document</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The webpage that Azure Storage serves for requests to the root of a website or any subfolder. For example, index.html. The value is case-sensitive.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








---
title: "Service"
block_external_search_index: true
---

Manages an API Management Service.

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/api_management.html.markdown.



## Create a Service Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/apimanagement/#Service">Service</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/apimanagement/#ServiceArgs">ServiceArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">Service</span><span class="p">(resource_name, opts=None, </span>additional_locations=None<span class="p">, </span>certificates=None<span class="p">, </span>hostname_configuration=None<span class="p">, </span>identity=None<span class="p">, </span>location=None<span class="p">, </span>name=None<span class="p">, </span>notification_sender_email=None<span class="p">, </span>policy=None<span class="p">, </span>protocols=None<span class="p">, </span>publisher_email=None<span class="p">, </span>publisher_name=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>security=None<span class="p">, </span>sign_in=None<span class="p">, </span>sign_up=None<span class="p">, </span>sku_name=None<span class="p">, </span>tags=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewService<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceArgs">ServiceArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#Service">Service</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Apimanagement.Service.html">Service</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.ApiManagement.Inputs.ServiceArgs.html">ServiceArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Additional<wbr>Location<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Certificate<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Hostname<wbr>Configuration<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Identity<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Protocols<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Security<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Sign<wbr>In<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Sign<wbr>Up<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">[]Service<wbr>Additional<wbr>Location</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">[]Service<wbr>Certificate</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">*Service<wbr>Hostname<wbr>Configuration</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">*Service<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">*Service<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">*Service<wbr>Protocols</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">*Service<wbr>Security</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">*Service<wbr>Sign<wbr>In</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">*Service<wbr>Sign<wbr>Up</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">Service<wbr>Additional<wbr>Location[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">Service<wbr>Certificate[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Service<wbr>Hostname<wbr>Configuration?</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Service<wbr>Identity?</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Service<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Service<wbr>Protocols?</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Service<wbr>Security?</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Service<wbr>Sign<wbr>In?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Service<wbr>Sign<wbr>Up?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>additional_<wbr>locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">List[Service<wbr>Additional<wbr>Location]</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">List[Service<wbr>Certificate]</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hostname_<wbr>configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Dict[Service<wbr>Hostname<wbr>Configuration]</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Dict[Service<wbr>Identity]</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification_<wbr>sender_<wbr>email</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Dict[Service<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Dict[Service<wbr>Protocols]</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>publisher_<wbr>email</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>publisher_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Dict[Service<wbr>Security]</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign_<wbr>in</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Dict[Service<wbr>Sign<wbr>In]</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign_<wbr>up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Dict[Service<wbr>Sign<wbr>Up]</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>sku_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## Service Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Additional<wbr>Location&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Certificate&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Gateway<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Hostname<wbr>Configuration</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Identity?</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Management<wbr>Api<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Portal<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Protocols</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scm<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Security</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Sign<wbr>In</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Outputs.<wbr>Service<wbr>Sign<wbr>Up</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">[]Service<wbr>Additional<wbr>Location</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">[]Service<wbr>Certificate</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Gateway<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Service<wbr>Hostname<wbr>Configuration</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">*Service<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Management<wbr>Api<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Service<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Portal<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Service<wbr>Protocols</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scm<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Service<wbr>Security</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Service<wbr>Sign<wbr>In</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Service<wbr>Sign<wbr>Up</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">Service<wbr>Additional<wbr>Location[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">Service<wbr>Certificate[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>gateway<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Service<wbr>Hostname<wbr>Configuration</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Service<wbr>Identity?</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>management<wbr>Api<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Service<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>portal<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Service<wbr>Protocols</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scm<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Service<wbr>Security</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Service<wbr>Sign<wbr>In</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Service<wbr>Sign<wbr>Up</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>additional_<wbr>locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">List[Service<wbr>Additional<wbr>Location]</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">List[Service<wbr>Certificate]</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>gateway_<wbr>regional_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>gateway_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>hostname_<wbr>configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Dict[Service<wbr>Hostname<wbr>Configuration]</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Dict[Service<wbr>Identity]</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>management_<wbr>api_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>notification_<wbr>sender_<wbr>email</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Dict[Service<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>portal_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Dict[Service<wbr>Protocols]</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>public_<wbr>ip_<wbr>addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>publisher_<wbr>email</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>publisher_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scm_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Dict[Service<wbr>Security]</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>sign_<wbr>in</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Dict[Service<wbr>Sign<wbr>In]</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>sign_<wbr>up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Dict[Service<wbr>Sign<wbr>Up]</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>sku_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing Service Resource

Get an existing Service resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">pulumi.Input&lt;pulumi.ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/apimanagement/#ServiceState">ServiceState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/apimanagement/#Service">Service</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>additional_locations=None<span class="p">, </span>certificates=None<span class="p">, </span>gateway_regional_url=None<span class="p">, </span>gateway_url=None<span class="p">, </span>hostname_configuration=None<span class="p">, </span>identity=None<span class="p">, </span>location=None<span class="p">, </span>management_api_url=None<span class="p">, </span>name=None<span class="p">, </span>notification_sender_email=None<span class="p">, </span>policy=None<span class="p">, </span>portal_url=None<span class="p">, </span>protocols=None<span class="p">, </span>public_ip_addresses=None<span class="p">, </span>publisher_email=None<span class="p">, </span>publisher_name=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>scm_url=None<span class="p">, </span>security=None<span class="p">, </span>sign_in=None<span class="p">, </span>sign_up=None<span class="p">, </span>sku_name=None<span class="p">, </span>tags=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetService<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">pulumi.IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceState">ServiceState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#Service">Service</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Apimanagement.Service.html">Service</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Pulumi.Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Apimanagement.ServiceState.html">ServiceState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Additional<wbr>Location<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Certificate<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Gateway<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Hostname<wbr>Configuration<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Identity<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Management<wbr>Api<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Portal<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Protocols<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scm<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Security<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Sign<wbr>In<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Sign<wbr>Up<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">[]Service<wbr>Additional<wbr>Location</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">[]Service<wbr>Certificate</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Gateway<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">*Service<wbr>Hostname<wbr>Configuration</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">*Service<wbr>Identity</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Management<wbr>Api<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">*Service<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Portal<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">*Service<wbr>Protocols</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scm<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">*Service<wbr>Security</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">*Service<wbr>Sign<wbr>In</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">*Service<wbr>Sign<wbr>Up</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>additional<wbr>Locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">Service<wbr>Additional<wbr>Location[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">Service<wbr>Certificate[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>gateway<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hostname<wbr>Configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Service<wbr>Hostname<wbr>Configuration?</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Service<wbr>Identity?</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>management<wbr>Api<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification<wbr>Sender<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Service<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>portal<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Service<wbr>Protocols?</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>publisher<wbr>Email</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>publisher<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scm<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Service<wbr>Security?</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign<wbr>In</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Service<wbr>Sign<wbr>In?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign<wbr>Up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Service<wbr>Sign<wbr>Up?</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sku<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>additional_<wbr>locations</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceadditionallocation">List[Service<wbr>Additional<wbr>Location]</a></span>
    </dt>
    <dd>{{% md %}}One or more `additional_location` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificates</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicecertificate">List[Service<wbr>Certificate]</a></span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>gateway_<wbr>regional_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>gateway_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the Gateway for the API Management Service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hostname_<wbr>configuration</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfiguration">Dict[Service<wbr>Hostname<wbr>Configuration]</a></span>
    </dt>
    <dd>{{% md %}}A `hostname_configuration` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>identity</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceidentity">Dict[Service<wbr>Identity]</a></span>
    </dt>
    <dd>{{% md %}}An `identity` block is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Azure location where the API Management Service exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>management_<wbr>api_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL for the Management API associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the API Management Service. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notification_<wbr>sender_<wbr>email</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Email address from which the notification will be sent.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicepolicy">Dict[Service<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A `policy` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>portal_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL for the Publisher Portal associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>protocols</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#serviceprotocols">Dict[Service<wbr>Protocols]</a></span>
    </dt>
    <dd>{{% md %}}A `protocols` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>public_<wbr>ip_<wbr>addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>publisher_<wbr>email</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The email of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>publisher_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of publisher/company.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group in which the API Management Service should be exist. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scm_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL for the SCM (Source Code Management) Endpoint associated with this API Management service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesecurity">Dict[Service<wbr>Security]</a></span>
    </dt>
    <dd>{{% md %}}A `security` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign_<wbr>in</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignin">Dict[Service<wbr>Sign<wbr>In]</a></span>
    </dt>
    <dd>{{% md %}}A `sign_in` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sign_<wbr>up</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignup">Dict[Service<wbr>Sign<wbr>Up]</a></span>
    </dt>
    <dd>{{% md %}}A `sign_up` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>sku_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}`sku_name` is a string consisting of two parts separated by an underscore(\_). The fist part is the `name`, valid values include: `Developer`, `Basic`, `Standard` and `Premium`. The second part is the `capacity` (e.g. the number of deployed units of the `sku`), which must be a positive `integer` (e.g. `Developer_1`).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Service<wbr>Additional<wbr>Location</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceAdditionalLocation">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceAdditionalLocation">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceAdditionalLocationArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceAdditionalLocationOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Azure Region in which the API Management Service should be expanded to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Azure Region in which the API Management Service should be expanded to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>gateway<wbr>Regional<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Azure Region in which the API Management Service should be expanded to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>public<wbr>Ip<wbr>Addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>gateway_<wbr>regional_<wbr>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the Regional Gateway for the API Management Service in the specified region.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Azure Region in which the API Management Service should be expanded to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>public_<wbr>ip_<wbr>addresses</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Public Static Load Balanced IP addresses of the API Management service in the additional location. Available only for Basic, Standard and Premium SKU.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Certificate</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceCertificate">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceCertificate">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceCertificateArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceCertificateOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Encoded<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded PFX Certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Store<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Certificate Store where this certificate should be stored. Possible values are `CertificateAuthority` and `Root`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Encoded<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded PFX Certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Store<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Certificate Store where this certificate should be stored. Possible values are `CertificateAuthority` and `Root`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>encoded<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded PFX Certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>store<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Certificate Store where this certificate should be stored. Possible values are `CertificateAuthority` and `Root`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>encoded<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded PFX Certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>store<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Certificate Store where this certificate should be stored. Possible values are `CertificateAuthority` and `Root`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Hostname<wbr>Configuration</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceHostnameConfiguration">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceHostnameConfiguration">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Managements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationmanagement">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Hostname<wbr>Configuration<wbr>Management<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `management` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Portals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationportal">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Hostname<wbr>Configuration<wbr>Portal<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `portal` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationproxy">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Hostname<wbr>Configuration<wbr>Proxy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `proxy` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scms</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationscm">List&lt;Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Hostname<wbr>Configuration<wbr>Scm<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}One or more `scm` blocks as documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Managements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationmanagement">[]Service<wbr>Hostname<wbr>Configuration<wbr>Management</a></span>
    </dt>
    <dd>{{% md %}}One or more `management` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Portals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationportal">[]Service<wbr>Hostname<wbr>Configuration<wbr>Portal</a></span>
    </dt>
    <dd>{{% md %}}One or more `portal` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationproxy">[]Service<wbr>Hostname<wbr>Configuration<wbr>Proxy</a></span>
    </dt>
    <dd>{{% md %}}One or more `proxy` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scms</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationscm">[]Service<wbr>Hostname<wbr>Configuration<wbr>Scm</a></span>
    </dt>
    <dd>{{% md %}}One or more `scm` blocks as documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>managements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationmanagement">Service<wbr>Hostname<wbr>Configuration<wbr>Management[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `management` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>portals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationportal">Service<wbr>Hostname<wbr>Configuration<wbr>Portal[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `portal` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationproxy">Service<wbr>Hostname<wbr>Configuration<wbr>Proxy[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `proxy` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scms</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationscm">Service<wbr>Hostname<wbr>Configuration<wbr>Scm[]?</a></span>
    </dt>
    <dd>{{% md %}}One or more `scm` blocks as documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>managements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationmanagement">List[Service<wbr>Hostname<wbr>Configuration<wbr>Management]</a></span>
    </dt>
    <dd>{{% md %}}One or more `management` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>portals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationportal">List[Service<wbr>Hostname<wbr>Configuration<wbr>Portal]</a></span>
    </dt>
    <dd>{{% md %}}One or more `portal` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationproxy">List[Service<wbr>Hostname<wbr>Configuration<wbr>Proxy]</a></span>
    </dt>
    <dd>{{% md %}}One or more `proxy` blocks as documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scms</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicehostnameconfigurationscm">List[Service<wbr>Hostname<wbr>Configuration<wbr>Scm]</a></span>
    </dt>
    <dd>{{% md %}}One or more `scm` blocks as documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Hostname<wbr>Configuration<wbr>Management</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceHostnameConfigurationManagement">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceHostnameConfigurationManagement">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationManagementArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationManagementOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>vault_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Hostname<wbr>Configuration<wbr>Portal</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceHostnameConfigurationPortal">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceHostnameConfigurationPortal">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationPortalArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationPortalOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>vault_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Hostname<wbr>Configuration<wbr>Proxy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceHostnameConfigurationProxy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceHostnameConfigurationProxy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationProxyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationProxyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Default<wbr>Ssl<wbr>Binding</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Is the certificate associated with this Hostname the Default SSL Certificate? This is used when an SNI header isn't specified by a client. Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Default<wbr>Ssl<wbr>Binding</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Is the certificate associated with this Hostname the Default SSL Certificate? This is used when an SNI header isn't specified by a client. Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>default<wbr>Ssl<wbr>Binding</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Is the certificate associated with this Hostname the Default SSL Certificate? This is used when an SNI header isn't specified by a client. Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Base64 Encoded Certificate.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password associated with the certificate provided above.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>default<wbr>Ssl<wbr>Binding</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is the certificate associated with this Hostname the Default SSL Certificate? This is used when an SNI header isn't specified by a client. Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>vault_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Hostname<wbr>Configuration<wbr>Scm</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceHostnameConfigurationScm">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceHostnameConfigurationScm">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationScmArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceHostnameConfigurationScmOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Vault<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}One or more (up to 10) `certificate` blocks as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>certificate<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password for the certificate.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Hostname to use for the Management API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>vault_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the Key Vault Secret containing the SSL Certificate, which must be should be of the type `application/x-pkcs12`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>negotiate<wbr>Client<wbr>Certificate</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Client Certificate Negotiation be enabled for this Hostname? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Identity</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceIdentity">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceIdentity">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceIdentityArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceIdentityOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Principal<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Principal ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tenant<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Tenant ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the type of Managed Service Identity that should be configured on this API Management Service. At this time the only supported value is`SystemAssigned`.
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
    <dd>{{% md %}}The Principal ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tenant<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Tenant ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the type of Managed Service Identity that should be configured on this API Management Service. At this time the only supported value is`SystemAssigned`.
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
    <dd>{{% md %}}The Principal ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tenant<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Tenant ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the type of Managed Service Identity that should be configured on this API Management Service. At this time the only supported value is`SystemAssigned`.
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
    <dd>{{% md %}}The Principal ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tenant_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Tenant ID associated with this Managed Service Identity.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the type of Managed Service Identity that should be configured on this API Management Service. At this time the only supported value is`SystemAssigned`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServicePolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServicePolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServicePolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServicePolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Xml<wbr>Content</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The XML Content for this Policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Xml<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}A link to an API Management Policy XML Document, which must be publicly available.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Xml<wbr>Content</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The XML Content for this Policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Xml<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}A link to an API Management Policy XML Document, which must be publicly available.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>xml<wbr>Content</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The XML Content for this Policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>xml<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}A link to an API Management Policy XML Document, which must be publicly available.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>xml_<wbr>content</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The XML Content for this Policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>xml_<wbr>link</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}A link to an API Management Policy XML Document, which must be publicly available.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Protocols</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceProtocols">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceProtocols">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceProtocolsArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceProtocolsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Http2</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should HTTP/2 be supported by the API Management Service? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Http2</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should HTTP/2 be supported by the API Management Service? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Http2</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should HTTP/2 be supported by the API Management Service? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>http2</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should HTTP/2 be supported by the API Management Service? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Security</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceSecurity">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceSecurity">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSecurityArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSecurityOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Backend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Backend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Backend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Frontend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Frontend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Frontend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Triple<wbr>Des<wbr>Ciphers</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Should the `TLS_RSA_WITH_3DES_EDE_CBC_SHA` cipher be enabled for alL TLS versions (1.0, 1.1 and 1.2)? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Backend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Backend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Backend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Frontend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Frontend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Frontend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Triple<wbr>Des<wbr>Ciphers</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Should the `TLS_RSA_WITH_3DES_EDE_CBC_SHA` cipher be enabled for alL TLS versions (1.0, 1.1 and 1.2)? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Backend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Backend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Backend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Frontend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Frontend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Frontend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Triple<wbr>Des<wbr>Ciphers</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Should the `TLS_RSA_WITH_3DES_EDE_CBC_SHA` cipher be enabled for alL TLS versions (1.0, 1.1 and 1.2)? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Backend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Backend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Backend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the backend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Frontend<wbr>Ssl30</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should SSL 3.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Frontend<wbr>Tls10</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.0 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Frontend<wbr>Tls11</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should TLS 1.1 be enabled on the frontend of the gateway? Defaults to `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Triple<wbr>Des<wbr>Ciphers</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should the `TLS_RSA_WITH_3DES_EDE_CBC_SHA` cipher be enabled for alL TLS versions (1.0, 1.1 and 1.2)? Defaults to `false`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Sign<wbr>In</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceSignIn">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceSignIn">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSignInArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSignInOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should anonymous users be redirected to the sign in page?
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
    <dd>{{% md %}}Should anonymous users be redirected to the sign in page?
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
    <dd>{{% md %}}Should anonymous users be redirected to the sign in page?
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
    <dd>{{% md %}}Should anonymous users be redirected to the sign in page?
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Sign<wbr>Up</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceSignUp">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceSignUp">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSignUpArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSignUpOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Can users sign up on the development portal?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Terms<wbr>Of<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignuptermsofservice">Pulumi.<wbr>Azure.<wbr>Api<wbr>Management.<wbr>Inputs.<wbr>Service<wbr>Sign<wbr>Up<wbr>Terms<wbr>Of<wbr>Service<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A `terms_of_service` block as defined below.
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
    <dd>{{% md %}}Can users sign up on the development portal?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Terms<wbr>Of<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignuptermsofservice">Service<wbr>Sign<wbr>Up<wbr>Terms<wbr>Of<wbr>Service</a></span>
    </dt>
    <dd>{{% md %}}A `terms_of_service` block as defined below.
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
    <dd>{{% md %}}Can users sign up on the development portal?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>terms<wbr>Of<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignuptermsofservice">Service<wbr>Sign<wbr>Up<wbr>Terms<wbr>Of<wbr>Service</a></span>
    </dt>
    <dd>{{% md %}}A `terms_of_service` block as defined below.
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
    <dd>{{% md %}}Can users sign up on the development portal?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>terms<wbr>Of<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#servicesignuptermsofservice">Dict[Service<wbr>Sign<wbr>Up<wbr>Terms<wbr>Of<wbr>Service]</a></span>
    </dt>
    <dd>{{% md %}}A `terms_of_service` block as defined below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Service<wbr>Sign<wbr>Up<wbr>Terms<wbr>Of<wbr>Service</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ServiceSignUpTermsOfService">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ServiceSignUpTermsOfService">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSignUpTermsOfServiceArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/apimanagement?tab=doc#ServiceSignUpTermsOfServiceOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Consent<wbr>Required</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should the user be asked for consent during sign up?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Terms of Service be displayed during sign up?.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Text</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Terms of Service which users are required to agree to in order to sign up.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Consent<wbr>Required</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should the user be asked for consent during sign up?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Terms of Service be displayed during sign up?.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Text</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Terms of Service which users are required to agree to in order to sign up.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>consent<wbr>Required</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Should the user be asked for consent during sign up?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Should Terms of Service be displayed during sign up?.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>text</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Terms of Service which users are required to agree to in order to sign up.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>consent<wbr>Required</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should the user be asked for consent during sign up?
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Should Terms of Service be displayed during sign up?.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>text</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Terms of Service which users are required to agree to in order to sign up.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







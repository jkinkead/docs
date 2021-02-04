
---
title: "UserContact"
title_tag: "Resource UserContact | Package opsgenie"
meta_desc: "Explore the UserContact resource of the opsgenie package, including examples, input properties, output properties, lookup functions, and supporting types. Manages a User Contact."
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Manages a User Contact.

{{% examples %}}
## Example Usage

{{< chooser language "typescript,python,go,csharp" / >}}

{{% example csharp %}}
```csharp
using Pulumi;
using Opsgenie = Pulumi.Opsgenie;

class MyStack : Stack
{
    public MyStack()
    {
        var sms = new Opsgenie.UserContact("sms", new Opsgenie.UserContactArgs
        {
            Method = "sms",
            To = "39-123",
            Username = opsgenie_user.Exampleuser.Username,
        });
        var email = new Opsgenie.UserContact("email", new Opsgenie.UserContactArgs
        {
            Method = "email",
            To = "fahri@opsgenie.com",
            Username = opsgenie_user.Exampleuser.Username,
        });
        var voice = new Opsgenie.UserContact("voice", new Opsgenie.UserContactArgs
        {
            Method = "voice",
            To = "39-123",
            Username = opsgenie_user.Exampleuser.Username,
        });
    }

}
```

{{% /example %}}

{{% example go %}}
```go
package main

import (
	"github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/"
	"github.com/pulumi/pulumi/sdk/v2/go/pulumi"
)

func main() {
	pulumi.Run(func(ctx *pulumi.Context) error {
		_, err := opsgenie.NewUserContact(ctx, "sms", &opsgenie.UserContactArgs{
			Method:   pulumi.String("sms"),
			To:       pulumi.String("39-123"),
			Username: pulumi.Any(opsgenie_user.Exampleuser.Username),
		})
		if err != nil {
			return err
		}
		_, err = opsgenie.NewUserContact(ctx, "email", &opsgenie.UserContactArgs{
			Method:   pulumi.String("email"),
			To:       pulumi.String("fahri@opsgenie.com"),
			Username: pulumi.Any(opsgenie_user.Exampleuser.Username),
		})
		if err != nil {
			return err
		}
		_, err = opsgenie.NewUserContact(ctx, "voice", &opsgenie.UserContactArgs{
			Method:   pulumi.String("voice"),
			To:       pulumi.String("39-123"),
			Username: pulumi.Any(opsgenie_user.Exampleuser.Username),
		})
		if err != nil {
			return err
		}
		return nil
	})
}
```

{{% /example %}}

{{% example python %}}
```python
import pulumi
import pulumi_opsgenie as opsgenie

sms = opsgenie.UserContact("sms",
    method="sms",
    to="39-123",
    username=opsgenie_user["exampleuser"]["username"])
email = opsgenie.UserContact("email",
    method="email",
    to="fahri@opsgenie.com",
    username=opsgenie_user["exampleuser"]["username"])
voice = opsgenie.UserContact("voice",
    method="voice",
    to="39-123",
    username=opsgenie_user["exampleuser"]["username"])
```

{{% /example %}}

{{% example typescript %}}

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as opsgenie from "@pulumi/opsgenie";

const sms = new opsgenie.UserContact("sms", {
    method: "sms",
    to: "39-123",
    username: opsgenie_user_exampleuser.username,
});
const email = new opsgenie.UserContact("email", {
    method: "email",
    to: "fahri@opsgenie.com",
    username: opsgenie_user_exampleuser.username,
});
const voice = new opsgenie.UserContact("voice", {
    method: "voice",
    to: "39-123",
    username: opsgenie_user_exampleuser.username,
});
```

{{% /example %}}

{{% /examples %}}


## Create a UserContact Resource {#create}
{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/opsgenie/#UserContact">UserContact</a></span><span class="p">(</span><span class="nx">name</span><span class="p">:</span> <span class="nx">string</span><span class="p">, </span><span class="nx">args</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/opsgenie/#UserContactArgs">UserContactArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nx"><a href="/docs/reference/pkg/python/pulumi_opsgenie/#pulumi_opsgenie.UserContact">UserContact</a></span><span class="p">(</span><span class="nx">resource_name</span><span class="p">:</span> <span class="nx">str</span><span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.ResourceOptions">Optional[ResourceOptions]</a></span> = None<span class="p">, </span><span class="nx">enabled</span><span class="p">:</span> <span class="nx">Optional[bool]</span> = None<span class="p">, </span><span class="nx">method</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">to</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">username</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/?tab=doc#UserContact">NewUserContact</a></span><span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span><span class="p"> </span><span class="nx">string</span><span class="p">, </span><span class="nx">args</span><span class="p"> </span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/?tab=doc#UserContactArgs">UserContactArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/?tab=doc#UserContact">UserContact</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Opsgenie/Pulumi.Opsgenie.UserContact.html">UserContact</a></span><span class="p">(</span><span class="nx">string</span><span class="p"> </span><span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Opsgenie/Pulumi.Opsgenie.UserContactArgs.html">UserContactArgs</a></span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
  
    <dt
        class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>
      The unique name of the resource.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>args</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="/docs/reference/pkg/nodejs/pulumi/opsgenie/#UserContactArgs">UserContactArgs</a></span>
    </dt>
    <dd>
      The arguments to resource properties.
    </dd>
  
    <dt
        class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span>
    </dt>
    <dd>
      Bag of options to control resource&#39;s behavior.
    </dd>
  

</dl>

{{% /choosable %}}

{{% choosable language python %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type">
            <a href="/docs/reference/pkg/python/pulumi/#pulumi.ResourceOptions">ResourceOptions</a>
        </span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
  
    <dt
        class="property-optional" title="Optional">
        <span>ctx</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span>
    </dt>
    <dd>
      Context object for the current deployment.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>
      The unique name of the resource.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>args</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/?tab=doc#UserContactArgs">UserContactArgs</a></span>
    </dt>
    <dd>
      The arguments to resource properties.
    </dd>
  
    <dt
        class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span>
    </dt>
    <dd>
      Bag of options to control resource&#39;s behavior.
    </dd>
  

</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
  
    <dt
        class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>
      The unique name of the resource.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>args</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="/docs/reference/pkg/dotnet/Pulumi.Opsgenie/Pulumi.Opsgenie.UserContactArgs.html">UserContactArgs</a></span>
    </dt>
    <dd>
      The arguments to resource properties.
    </dd>
  
    <dt
        class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>
    </dt>
    <dd>
      Bag of options to control resource&#39;s behavior.
    </dd>
  

</dl>

{{% /choosable %}}

## UserContact Resource Properties {#properties}

To learn more about resource properties and how to use them, see [Inputs and Outputs]({{< relref "/docs/intro/concepts/programming-model#outputs" >}}) in the Programming Model docs.

### Inputs

The UserContact resource accepts the following [input]({{< relref "/docs/intro/concepts/programming-model#outputs" >}}) properties:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="method_csharp">
<a href="#method_csharp" style="color: inherit; text-decoration: inherit;">Method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="to_csharp">
<a href="#to_csharp" style="color: inherit; text-decoration: inherit;">To</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="username_csharp">
<a href="#username_csharp" style="color: inherit; text-decoration: inherit;">Username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="enabled_csharp">
<a href="#enabled_csharp" style="color: inherit; text-decoration: inherit;">Enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="method_go">
<a href="#method_go" style="color: inherit; text-decoration: inherit;">Method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="to_go">
<a href="#to_go" style="color: inherit; text-decoration: inherit;">To</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="username_go">
<a href="#username_go" style="color: inherit; text-decoration: inherit;">Username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="enabled_go">
<a href="#enabled_go" style="color: inherit; text-decoration: inherit;">Enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="method_nodejs">
<a href="#method_nodejs" style="color: inherit; text-decoration: inherit;">method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="to_nodejs">
<a href="#to_nodejs" style="color: inherit; text-decoration: inherit;">to</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="username_nodejs">
<a href="#username_nodejs" style="color: inherit; text-decoration: inherit;">username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="enabled_nodejs">
<a href="#enabled_nodejs" style="color: inherit; text-decoration: inherit;">enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="method_python">
<a href="#method_python" style="color: inherit; text-decoration: inherit;">method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="to_python">
<a href="#to_python" style="color: inherit; text-decoration: inherit;">to</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="username_python">
<a href="#username_python" style="color: inherit; text-decoration: inherit;">username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="enabled_python">
<a href="#enabled_python" style="color: inherit; text-decoration: inherit;">enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}


### Outputs

All [input](#inputs) properties are implicitly available as output properties. Additionally, the UserContact resource produces the following output properties:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
</dl>
{{% /choosable %}}



## Look up an Existing UserContact Resource {#look-up}

Get an existing UserContact resource's state with the given name, ID, and optional extra properties used to qualify the lookup.
{{< chooser language "typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span><span class="p">:</span> <span class="nx">string</span><span class="p">, </span><span class="nx">id</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/opsgenie/#UserContactState">UserContactState</a></span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/opsgenie/#UserContact">UserContact</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class=nd>@staticmethod</span>
<span class="k">def </span><span class="nf">get</span><span class="p">(</span><span class="nx">resource_name</span><span class="p">:</span> <span class="nx">str</span><span class="p">, </span><span class="nx">id</span><span class="p">:</span> <span class="nx">str</span><span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.ResourceOptions">Optional[ResourceOptions]</a></span> = None<span class="p">, </span><span class="nx">enabled</span><span class="p">:</span> <span class="nx">Optional[bool]</span> = None<span class="p">, </span><span class="nx">method</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">to</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">username</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">) -&gt;</span> UserContact</code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetUserContact<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span><span class="p"> </span><span class="nx">string</span><span class="p">, </span><span class="nx">id</span><span class="p"> </span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/?tab=doc#UserContactState">UserContactState</a></span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-opsgenie/sdk/go/opsgenie/?tab=doc#UserContact">UserContact</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Opsgenie/Pulumi.Opsgenie.UserContact.html">UserContact</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx">string</span><span class="p"> </span><span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input-1.html">Input&lt;string&gt;</a></span><span class="p"> </span><span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Opsgenie/Pulumi.Opsgenie..UserContactState.html">UserContactState</a></span><span class="p">? </span><span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span id="state_enabled_csharp">
<a href="#state_enabled_csharp" style="color: inherit; text-decoration: inherit;">Enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_method_csharp">
<a href="#state_method_csharp" style="color: inherit; text-decoration: inherit;">Method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_to_csharp">
<a href="#state_to_csharp" style="color: inherit; text-decoration: inherit;">To</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_username_csharp">
<a href="#state_username_csharp" style="color: inherit; text-decoration: inherit;">Username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="state_enabled_go">
<a href="#state_enabled_go" style="color: inherit; text-decoration: inherit;">Enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_method_go">
<a href="#state_method_go" style="color: inherit; text-decoration: inherit;">Method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_to_go">
<a href="#state_to_go" style="color: inherit; text-decoration: inherit;">To</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_username_go">
<a href="#state_username_go" style="color: inherit; text-decoration: inherit;">Username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="state_enabled_nodejs">
<a href="#state_enabled_nodejs" style="color: inherit; text-decoration: inherit;">enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_method_nodejs">
<a href="#state_method_nodejs" style="color: inherit; text-decoration: inherit;">method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_to_nodejs">
<a href="#state_to_nodejs" style="color: inherit; text-decoration: inherit;">to</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_username_nodejs">
<a href="#state_username_nodejs" style="color: inherit; text-decoration: inherit;">username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="state_enabled_python">
<a href="#state_enabled_python" style="color: inherit; text-decoration: inherit;">enabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable contact of the user in OpsGenie. Default value is true.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_method_python">
<a href="#state_method_python" style="color: inherit; text-decoration: inherit;">method</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This parameter is the contact method of user and should be one of email, sms or voice. Please note that adding mobile is not supported from API.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_to_python">
<a href="#state_to_python" style="color: inherit; text-decoration: inherit;">to</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}to field is the address of given method.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="state_username_python">
<a href="#state_username_python" style="color: inherit; text-decoration: inherit;">username</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The username for contact.(reference)
{{% /md %}}</dd>
</dl>
{{% /choosable %}}





## Import


Users can be imported using the `id`, e.g.

```sh
 $ pulumi import opsgenie:index/userContact:UserContact testcontact username/contactId`
```

 For this example- Username = `genie@awesometeam.com`

- Contact Id = `2d1a78d0-c13e-47d3-af0a-8b6d0cc2b7b1`

```sh
 $ pulumi import opsgenie:index/userContact:UserContact testcontact genie@awesometeam.com/2d1a78d0-c13e-47d3-af0a-8b6d0cc2b7b1`
```




<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-opsgenie">https://github.com/pulumi/pulumi-opsgenie</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
	<dt>Notes</dt>
	<dd>This Pulumi package is based on the [`opsgenie` Terraform Provider](https://github.com/opsgenie/terraform-provider-opsgenie).</dd>
</dl>

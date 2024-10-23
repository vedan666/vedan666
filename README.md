![Introduction](./Introduction.gif)

```hcl
## HCL Introduction

variable "name" {
  description = "Name of the DevOps Engineer"
  default     = "Vedant"
}

variable "focus_areas" {
  description = "Key focus areas of expertise"
  default     = "Azure, Terraform, and cloud automation"
}

resource "intro_group" "introduction" {
  provisioner "local-exec" {
    command = <<-EOT
      echo -e "Welcome to my GitHub Page.
      \n
      I'm ${var.name}, a DevOps Engineer particularly focusing on ${var.focus_areas}.
      \n 
      I enjoy making complex tech stuff easier, automating processes, and tweaking systems for better performance."
    EOT
  }
}

output "github_intro" {
  value = "Introduction has been printed to the console."
}

```

Welcome to my GitHub Page.
I'm Vedant, a DevOps Engineer particularly focusing on Azure, Terraform, and cloud automation. I enjoy making complex tech stuff easier, automating processes, and tweaking systems for better performance

In my journey, I’ve had the opportunity to work on large-scale cloud deployments, design resilient systems, and collaborate with cross-functional teams to deliver seamless operations.

Thanks for visiting and I'd love to [connect](https://www.linkedin.com/in/vedant-shukla-1a036a314/)!

## My favorite tools and technologies ⚙️

Here are tools and technologies that I have worked with and am interested in:

<table>
  <tr>
    <td>
      <img src="icons/Azure-Dark.svg" width="100" />
      <br /> Azure
    </td>
    <td>
      <img src="icons/AWS-Dark.svg" width="100" />
      <br /> AWS
    </td>
    <td>
      <img src="icons/GCP-Dark.svg" width="100" />
      <br /> GCP
    </td>
    <td>
      <img src="icons/Terraform-Dark.svg" width="100" />
      <br /> Terraform
    </td>
    <td>
      <img src="icons/Python-Dark.svg" width="100" />
      <br /> Python
    </td>
    <td>
      <img src="icons/Docker.svg" width="100" />
      <br /> Docker
    </td>
  </tr>
  <tr>
    <td>
      <img src="icons/Kubernetes.svg" width="100" />
      <br /> Kubernetes
    </td>
    <td>
      <img src="icons/Nginx.svg" width="100" />
      <br /> Nginx
    </td>
    <td>
      <img src="icons/Git.svg" width="100" />
      <br /> Git
    </td>
    <td>
      <img src="icons/Github-Dark.svg" width="100" />
      <br /> GitHub
    </td>
    <td>
      <img src="icons/Prometheus.svg" width="100" />
      <br /> Prometheus
    </td>
    <td>
      <img src="icons/Grafana-Dark.svg" width="100" />
      <br /> Grafana
    </td>
  </tr>
</table>



## 🏆 My Stats:

<div style="display: flex; justify-content: space-evenly;
;">

  <a href="https://github.com/vedan666/github-readme-stats">
    <img src="https://github-readme-stats.vercel.app/api?username=vedan666" alt="Vedant's GitHub stats" />
  </a>

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vedan666&layout=compact" alt="Top Languages" />

</div>


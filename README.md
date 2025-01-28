![Introduction](./Introduction.gif)

```yaml
variables:
  name:
    description: "Name of the DevOps Engineer"
    default: "Vedant"
  focus_areas:
    description: "Key focus areas of expertise"
    default: "Azure, Terraform, Yaml, and CICD pipelines"

resources:
  - intro_group:
      name: "introduction"
      provisioner:
        local-exec:
          command: |
            echo -e "Welcome to my GitHub Page.
            \n
            I'm ${name}, a DevOps Engineer particularly focusing on ${focus_areas}.
            \n
            I enjoy making complex tech stuff easier, automating processes, and tweaking systems for better performance."

outputs:
  github_intro:
    value: "Introduction has been printed to the console."

```

Thanks for visiting 😊 and I'd love to [connect](https://www.linkedin.com/in/vedant-shukla-1a036a314/)!

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


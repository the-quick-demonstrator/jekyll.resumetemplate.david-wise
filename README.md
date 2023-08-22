{% assign linkedin = "https://www.linkedin.com/in/leon-hunter" %}
{% assign email    = "xleonhunter@gmail.com" %}
{% assign username = "git-leon" %}
{% capture repository %}
    https://{{ username }}.github.io/resume
{% endcapture %}

# {{ name }}

<table>
   <tr>
      <td>
         <img src="https://github-readme-stats.vercel.app/api?username={{ username }}&show_icons=true&theme=dracula">         
      </td>
      <td>
         <img src="https://github-readme-stats.vercel.app/api/top-langs/?username={{ username }}&layout=compact&theme=dracula&hide=roff,tsql,c">
      </td>
   </tr>
</table>

<link rel="stylesheet" type="text/css" media="all" href="./assets/css/style.css" />

* Click [here](https://{{ username }}.github.io/{{ username }}) to view full portfolio_


### Education
* ZipCodeWilmington School of Coding - _March 2023 - May 2023_
* _[Certificate of Completion](./bachelors-degree.pdf)_



### Contact Information
* **Email**: [`{{ email }}`](mailto:{{ email }})
* **Website:** [`{{ repository }}`]({{ repository }})
* **LinkedIn:** [`{{ linkedin }}`]({{ linkedin }})
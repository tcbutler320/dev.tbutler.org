---
layout: home
---  

```text
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░████████╗██╗░░░██╗██╗░░░░░███████╗██████╗░░░██████╗░██╗░░░██╗████████╗██╗░░░░░███████╗██████╗░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░╚══██╔══╝╚██╗░██╔╝██║░░░░░██╔════╝██╔══██╗░░██╔══██╗██║░░░██║╚══██╔══╝██║░░░░░██╔════╝██╔══██╗░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░██║░░░░╚████╔╝░██║░░░░░█████╗░░██████╔╝░░██████╦╝██║░░░██║░░░██║░░░██║░░░░░█████╗░░██████╔╝░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░██║░░░░░╚██╔╝░░██║░░░░░██╔══╝░░██╔══██╗░░██╔══██╗██║░░░██║░░░██║░░░██║░░░░░██╔══╝░░██╔══██╗░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░██║░░░░░░██║░░░███████╗███████╗██║░░██║░░██████╦╝╚██████╔╝░░░██║░░░███████╗███████╗██║░░██║░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░╚═╝░░░░░░╚═╝░░░╚══════╝╚══════╝╚═╝░░╚═╝░░╚═════╝░░╚═════╝░░░░╚═╝░░░╚══════╝╚══════╝╚═╝░░╚═╝░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ Independent Security Researcher ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
``` 

I’m an independent security researcher with industry experience in penetration testing, cyber risk consulting, and software engineering. 

## 🏆 Education and Certifications  

- The Pennsylvania State University, BS Security and Risk Analysis, BA Criminology
- eLearnSecurity's Web Application Penetration Tester (eWPT)
- eLearnSecurity's Junior Penetration Tester (eWPT)
 

## 🏆 Awards and Recognition   

- Motorola [Bug Bounty Hall of Fame](https://www.motorolasolutions.com/en_us/about/security-vulnerability/hall-of-fame.html) 2021 Member

## 👾 Disclosed Vulnerabilities   

*Below is a list of vulnerabilities I've disclosed as part of bug bounties and responsible disclosure*  

<div id="archives">
  {% for vuln in site.data.vulns %}
    <div class="archive-group">
      <article class="archive-item">
        <div style="line-height:14px;height:14px; border-bottom:2px dotted;">
            <p style="text-align:left;">
              <a style="text-decoration: none;" href="{{ site.baseurl }}{{ vuln.url }}">{{vuln.Title}}</a>
              <span style="float:right;">
                  {{vuln.Date|date:'%B %d, %Y'}}
              </span>
            </p>
          </div>
      </article>
    </div>
  {% endfor %}
</div>

 
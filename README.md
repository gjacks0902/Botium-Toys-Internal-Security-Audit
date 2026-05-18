# Botium-Toys-Internal-Security-Audit

<h1>Contents</h1>
<ol>
  <li><a href="#about">About Audit</a></li>
  <li><a href="#scen">Scenario</a></li>
  <li><a href="#risk">Risk Assessment</a></li>
  <li><a href="#control">Controls Assessment</a></li>
  <li><a href="#comp">Compliance Checklist</a></li>
  <li><a href="#stake">Stakeholder Memorandum</a></li>
  <li><a href="#con">Conclusion</a></li>
</ol>

  <h2 id="about">About Audit</h2>
  <p>A internal security audit done for a fake company named Botium Toys, which was designed for the Google's Cybersecurity Professional Certification through Coursera.</p>
  <p>The goal of the internal security audit of Botium Toys is to access where the company stands in regards to compliance and business operations in relation with the recent growth of the company. This audit will provide more security by identifying and mitigating potential risks, threats, and vulnerabilities to valuable assets. As well as, giving a course of action for improving the companies overall security stance.</p>
  
  <h2 id="scen">Scenario</h2>
  <p>Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which  serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.</p>

  <p>Goals for internal audit:</p>
  <ul>
    <li>Establish policies and procedures to ensure compliance with regulations.</li>
    <li>Fortify system controls.</li>
    <li>Implement a system for employees so they require a low level of permissions nessesary.</li>
    <li>Adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF).</li>
  </ul>
  
  <h2 id="risk">Risk Assessment</h2>
  
  <h3>Risk Description</h3>
  <p>Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.</p>
    
  <h3>Control Best Practices</h3>
  <p>The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.</p>
    
  <h3>Risk Score</h3>
  <p>On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.</p>
    
  <h3>Additional Comments</h3>
  <p>The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure.</p>
  
  <h2 id="control">Controls Assessment</h2>
  <h3>Admisistrative Controls</h3>
    <table>
    <thead>
      <tr>
      <th>Control Name</th>
      <th>Control type and explanation</th>
      <th>Needs to be implemented (X)</th>
      <th>Priority</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Least Privilege</td>
        <td>Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs</td>
        <td>X</td>
        <td>High</td>
      </tr>
      <tr>
        <td>Disaster recovery plans</td>
        <td>Corrective; business continuity to ensure systems are able to run in the event of an incident</td>
        <td>X</td>
        <td>High</td>
      </tr>
      <tr>
        <td>Password policies</td>
        <td>Preventative; establish password strength rules to improve security/reduce likelihood of account compromise</td>
        <td>X</td>
        <td>High</td>
      </tr>
      <tr>
        <td>Access control policies</td>
        <td>Preventative; increase confidentiality and integrity of data</td>
        <td>X</td>
        <td>High</td>
      </tr>
      <tr>
        <td>Account management policies</td>
        <td>Preventative; reduce attack surface and limit overall impact from former employees</td>
        <td>X</td>
        <td>High</td>
      </tr>
      <tr>
        <td>Separation of duties</td>
        <td>Preventative; ensure no one has too much access, so that they can't abuse the system</td>
        <td>X</td>
        <td>High</td>
      </tr>
    </tbody>
    </table>
    
<h3>Technical Controls</h3>
  <table>
    <thead>
    <tr>
      <th>Control Name</th>
      <th>Control type and explanation</th>
      <th>Needs to be implemented (X)</th>
      <th>Priority</th>
    </tr>
    </thead>
    <tbody>
    <tr>
      <td>Firewall</td>
      <td>Preventative; firewalls are already in place to filter malicious traffic from entering</td>
      <td>NA</td>
      <td>NA</td>
    </tr>
    <tr>
      <td>Intrusion Detection System (IDS)</td>
      <td>Detective; allows IT team to identify possible intrusion quickly</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Encryption</td>
      <td>Deterrent; makes confidential information more secure (e.g., payment, social security numbers)</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Backups</td>
      <td>Corrective; allows for a disaster recovery plan; the ability to restore/recover from an event</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Password management system</td>
      <td>Preventative; password recovery and reset</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Antivirus (AV) software</td>
      <td>Preventative; detect and quarantine known threats</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Manual monitoring, maintenance, and intervention</td>
      <td>Preventative; required to identify and mitigate potential threats, risks, and vulnerabilities</td>
      <td>X</td>
      <td>High</td>
    </tr>
    </tbody>
  </table>
    
<h3>Physical Controls</h3>
  <table>
    <thead>
    <tr>
      <th>Control Name</th>
      <th>Control type and explanation</th>
      <th>Needs to be implemented (X)</th>
      <th>Priority</th>
    </tr>
    </thead>
    <tbody>
    <tr>
      <td>Time-controlled safe</td>
      <td>Deterrent; reduce attack surface/impact of physical threats</td>
      <td>X</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Adequate lighting</td>
      <td>Deterrent; limit “hiding” places to deter threats</td>
      <td>X</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Closed-circuit television (CCTV) surveillance</td>
      <td>Preventative/detective; can reduce risk of certain events; can be used after event for investigation</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Locking cabinets (for network gear)</td>
      <td>Preventative; increase integrity by preventing unauthorized personnel from physically accessing/modifying network infrastructure gear</td>
      <td>X</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Signage indicating alarm service provider</td>
      <td>Deterrent; makes the likelihood of a successful attack seem low</td>
      <td>X</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Locks</td>
      <td>Deterrent/Preventative; physical and digital assets are more secure</td>
      <td>X</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Fire detection and prevention (fire alarm, sprinkler system, etc.)</td>
      <td>Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.</td>
      <td>X</td>
      <td>Medium</td>
    </tr>
    </tbody>
  </table>
  
  <h2 id="comp">Compliance Checklist</h2>
  <ul>
    <li>General Data Protection Regulation (GDPR)</li>
    <ul>
      <li>The GDPR is a European Union (EU) general data regulation that protects the processing of EU citizens' data and their right to privacy in and out of EU territory. Additionally, if a breach occurs and a EU citizen's data is compromised, they must be informed within 72 hours of the incident.</li>
      <ol>
        <li>Botium Toys has been growing greatly and they want to expand their services to a global scale. Therefore, they need to ensure they're GDPR compliance is in the correct scope for accounting for the sensitive personal information for the EU.</li>
      </ol>
    </ul>
  </ul>

  <ul>
    <li>Payment Card Industry Data Security Standard (PCI DSS)</li>
    <ul>
      <li>PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure enviornment.</li>
      <ol>
        <li>The company needs to be able to protect their customers becasue of the online payments they accept. They must follow PCI DSS becuase they also now are accepting payments globally. Becuase of this they need to follow the requirements and compliance necessary, in order to avoid the serious consequences. Like data breaches, damaged reputations, and possible lawsuits.</li>
      </ol>
    </ul>
  </ul>
  
  <h2 id="stake">Stakeholder Memorandum</h2>
  
  
  
  <h2 id="con">Conclusion</h2>



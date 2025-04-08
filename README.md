<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

<p>This guide outlines the lifecycle of a support ticket from creation to resolution within the open-source help desk ticketing system <strong>osTicket</strong>. Understanding this flow helps ensure tickets are handled with efficiency, accountability, and clarity.</p>

<hr />

<h2>🌐 Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>🖥️ Operating Systems Used</h2>
<ul>
  <li>Windows 10 (22H2)</li>
</ul>

<hr />

<h2>🔄 osTicket Ticket Lifecycle Stages</h2>

<p>Tickets in osTicket go through four main lifecycle stages:</p>

<ol>
  <li><strong>Intake:</strong> A ticket is created by either a user or an agent. This is the entry point for the support request.</li>
  <li><strong>Assignment & Communication:</strong> The ticket is assigned to the appropriate department or agent. Communication begins with the end-user to gather more context or updates.</li>
  <li><strong>Working the Issue:</strong> The assigned agent investigates and works toward resolving the issue. This may involve updates, clarifications, or collaboration.</li>
  <li><strong>Resolution & Closure:</strong> Once resolved, the solution is confirmed with the user, and the ticket is officially closed.</li>
</ol>

<hr />

<h2>📊 Prioritizing Tickets Using SLAs (Service Level Agreements)</h2>

<p>
  SLAs help define resolution timeframes based on the severity of the issue. These agreements ensure timely responses and promote effective triage.
</p>

<ul>
  <li><strong>Sev-A (1 Hour, 24/7):</strong> Highest priority issues such as system-wide outages (e.g., toll system network down). These are escalated to the <strong>SysAdmins</strong> team for immediate attention.</li>
  <li><strong>Sev-B (4 Hours, 24/7):</strong> High-priority but not critical issues (e.g., CLM - Cash Logistics Manager app not working due to network errors). These are resolved within 4 hours.</li>
  <li><strong>Sev-C (8 Hours, Business Hours):</strong> Low-priority issues (e.g., password resets). Resolved within one business day.</li>
</ul>

<p>Adhering to SLAs ensures that urgent tickets are prioritized appropriately, while less critical issues are still addressed in a timely and structured manner.</p>

<hr />

<h2>⚖️ Ticket Triage</h2>

<p>Triaging is the process of evaluating and categorizing tickets based on their urgency and complexity. It involves deciding whether to:</p>

<ul>
  <li>Resolve the ticket immediately (if it’s simple or within the agent’s scope)</li>
  <li>Escalate the ticket to a higher-tier team for further investigation</li>
</ul>

<p>This step is crucial in maintaining workflow efficiency and ensuring no tickets fall through the cracks.</p>

<hr />

<h2>✅ Solving Problems and Closing Tickets</h2>

<p>Once the assigned agent identifies a solution:</p>

<ul>
  <li>The agent communicates the resolution to the user</li>
  <li>The ticket status is updated to reflect the resolution</li>
  <li>The ticket is officially marked as <strong>closed</strong> after user confirmation or follow-up</li>
</ul>

<p>This marks the final stage of the ticket’s lifecycle and is essential for maintaining proper documentation and resolution records.</p>

<hr />

<h2>📝 Summary</h2>

<p>
  The osTicket system provides a structured lifecycle for support tickets—from initial intake through resolution. 
  With clearly defined stages (Intake, Assignment, Working, and Resolution), combined with SLA-based prioritization 
  and effective triage, the support workflow becomes streamlined and reliable.
</p>

<p>
  Mastering this lifecycle ensures that support teams respond quickly to critical issues, manage workloads effectively, 
  and deliver consistent support experiences to users.
</p>

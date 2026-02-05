<p align="center">
  <img src="richmenu\richmenu.png" alt="Hospital Rich Menu Interface" width="550" style="border: 3px solid #007c91; border-radius: 15px;">
  <br>
  <em><strong>Exhibit A:</strong> Architectural Layout of Client-Side Service Interface (8-Grid System)</em>
</p>

---

| SYSTEM IDENTITY & GOVERNANCE | |
| :--- | :--- |
| **Institution** | Kamphaeng Phet Community Municipal Hospital |
| **Identifier** | KPC-HIS-LINEOA-001 |
| **Classification** | Internal Use Only (Confidential) |
| **Revision** | 1.0.0 |

---

| EVENT ROUTING & SERVICE PROTOCOLS | | |
| :--- | :--- | :--- |
| **Functional Domain** | **Triggering Keywords** | **Synthesis Protocol** |
| **Telemedicine** | เริ่มใช้บริการ, เริ่มต้น, ใช้งาน | `getTelemedSession()` |
| **Clinical Services** | ตรวจโรคทั่วไป, แพทย์แผนไทย, แพทย์แผนจีน | `getClinicalInquiry()` |
| **Service Info** | ข้อมูลเพิ่มเติม, บริการ, ดูเพิ่มเติม | `getMoreTelemed()` |
| **Knowledge Base** | คำถามที่พบบ่อย, FAQ, สาระสุขภาพ | `getFaqKnowledgeBase()` |
| **Public Relations** | ประชาสัมพันธ์, ข่าวสาร | `getLatestNews()` |
| **Navigation** | บริการของเรา, เมนูหลัก | `servicesQuickReply()` |
| **Contact/Profile** | ติดต่อเรา, เกี่ยวกับเรา | `getContactInfo()` |

---

<p align="center">
  <em><strong>System Architecture Logic Flow</strong></em>
</p>

---

| CORE ARCHITECTURAL SPECIFICATION | |
| :--- | :--- |
| **Component** | **Architectural Implementation** |
| **Interaction Layer** | Keyword-Driven Webhook for instant clinical triage |
| **Business Logic** | Protocol-Based Routing ensuring standardized response |
| **Data Integrity** | Real-time Transaction Logging for HA/Accreditation |
| **Gateway Design** | Synchronous Messaging Interface (LINE Platform) |

---

| METADATA & CONTACT | |
| :--- | :--- |
| **Architect** | Ratchanon Noknoy |
| **Collaboration** | Senior Professional Nursing Management Standards |
| **Status** | Production Ready |
| **Connect** | [LinkedIn](https://www.linkedin.com/in/ratchanon-noknoy/) / [GitHub](https://github.com/ratchanon-noknoy2318) |

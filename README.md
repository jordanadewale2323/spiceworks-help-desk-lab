# spiceworks-help-desk-lab
Hands-on Help Desk lab documenting real-world Spiceworks ticketing workflows, including ticket creation, user communication, troubleshooting, escalation, documentation, resolution, and ticket closure.

# Spiceworks Help Desk — Hands-On Ticketing Lab

## Lab Goal

The goal of this hands-on lab is to practice real-world Help Desk workflows using Spiceworks. The lab focuses on creating support tickets, understanding user requests, communicating with ticket holders, troubleshooting issues, escalating requests when appropriate, documenting actions, and closing tickets.

## Skills Practiced

- Creating and managing Help Desk tickets
- Categorizing and prioritizing requests
- Communicating with users
- Troubleshooting technical issues
- Documenting troubleshooting steps and resolutions
- Escalating requests that require additional authority
- Verifying resolutions
- Closing tickets

## Ticket Workflow

**Request → Ticket Creation → Investigation → Communication → Troubleshooting/Escalation → Resolution → Documentation → Closure**

---

# Ticket #001 — Speaker Not Working on Some Applications

## User Request

The user reported that their speakers worked properly with applications such as YouTube and Chrome, but there was no audio output from Adobe Premiere Pro. The user also provided availability for troubleshooting after a 10:00 AM meeting.

## Ticket Configuration

| Field | Value |
|---|---|
| Organization | JB |
| Contact | Jordan Adewale |
| Category | Hardware |
| Priority | Medium |
| Assignee | Jordan Adewale |
| Status | Open → Closed |

## 1. Ticket Creation

I created the ticket in Spiceworks and entered the user's reported problem, priority, category, organization, and contact information.

![Spiceworks Ticket Creation](images/ticket-001-create.png)

## 2. Communication With Ticket Holder

I reviewed the user's request and documented the troubleshooting communication in the ticket. The ticket holder explained that audio worked in other applications but not Adobe Premiere Pro.

I also documented the user's availability so troubleshooting could be coordinated appropriately.

![Ticket Communication](images/ticket-001-communication.png)

## 3. Troubleshooting and Resolution

I checked Adobe Premiere Pro's audio output settings and restarted the application. After the restart, audio was working properly.

The resolution was documented in the Spiceworks ticket:

> Issue resolved. Checked Premiere's audio output setting and restarted the app; audio is working properly now.

## 4. Ticket Closure

After resolving the issue, I closed the ticket in Spiceworks. The closed-ticket view confirms that the ticket was completed.

![Closed Ticket](images/ticket-001-closed.png)

### Result

**Status: Closed**

The issue was successfully resolved and documented.

---

# Ticket #002 — FinCalc Database Access Request

## User Request

The user requested access to the FinCalc database or asked that the request be handed over to someone with the appropriate authority.

## Initial Assessment

The request involved database access, so it required appropriate authorization. Rather than granting access without approval, I escalated the request to the appropriate team member.

## Ticket Information

| Field | Value |
|---|---|
| Ticket | #4 |
| Organization | JB |
| Category | Software |
| Priority | Medium |
| Status | Open |
| Requested Access | Read-only |
| User Account | adm001 |

## 1. Review of Request

I reviewed the user's request and identified that the requested database access required authorization.

## 2. Escalation

I documented the escalation in Spiceworks and provided the receiving team with the relevant information:

- User account: `adm001`
- Requested system: FinCalc
- Requested permission: Read-only access
- Reason: Requires a team member with the proper authority

![Spiceworks Escalation](images/ticket-002-escalation.png)

## 3. Communication

I communicated through the ticket that the request was being escalated and asked the receiving team to let me know if additional information was required.

## Result

The ticket remained **Open** while the authorized team handled the access request.

---

# Help Desk Skills Demonstrated

## Ticket Management

I practiced creating, updating, and closing tickets while keeping the ticket information organized.

## Customer Communication

I documented user requests, availability, troubleshooting updates, and resolution information directly in the ticket.

## Troubleshooting

I practiced identifying the likely scope of an issue, testing a solution, and documenting the result.

## Escalation

I practiced recognizing when a request required additional authority and escalating it instead of making an unauthorized change.

## Documentation

Each ticket records the request, actions taken, communication, resolution or escalation, and final status.

# Conclusion

This hands-on Spiceworks lab provided practice with the basic Help Desk ticket lifecycle. I worked with both a technical incident and an access request, communicated with ticket holders, documented troubleshooting, resolved an issue, escalated a request when additional authority was required, and closed a completed ticket.

The lab demonstrates practical experience with **ticketing, troubleshooting, communication, escalation, documentation, and ticket closure**.

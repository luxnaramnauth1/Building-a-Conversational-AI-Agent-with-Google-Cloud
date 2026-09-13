# Building-a-Conversational-AI-Agent-with-Google-Cloud
# ✈️ Flight Booker — Conversational AI Agent (Google Cloud)

A conversational AI agent built on **Google Cloud's Conversational Agents** platform that guides a user end-to-end through booking a flight ticket — from intent detection, to structured data collection, to a final booking confirmation.

This project was completed as part of the **Google Cloud Skills Boost** learning path *"Agentic AI on Google Cloud,"* specifically the hands-on lab **"Build a Basic Conversational Agent Flow."**

---

## 📖 Overview

Conversational Agents provides a visual, no-code/low-code approach to building chatbots and voice assistants. Instead of writing conversation logic in code, you design **flows** made of **pages**, each responsible for a step in the conversation, connected by routes and conditions.

This project models a real-world flight-booking scenario: a user tells the agent they want to book a flight, and the agent naturally guides them through providing the departure city, destination city, and travel date before confirming the trip.

## 🧩 How the Agent Is Structured

The `Default Start Flow` is built from three connected pages:

| Page | Purpose |
|---|---|
| **Start Page** | Entry point of the conversation. Detects user intent (e.g. *"I'd like to book a flight"*) and routes into the booking flow. |
| **Ticket Information** | Collects the required trip details through natural back-and-forth dialogue — departure city, destination city, and travel date. |
| **Confirm Trip** | Summarizes everything the agent captured and asks the user to confirm before the booking is finalized. |

<p align="center">
  <img src="assets/flow-builder-preview.png" alt="Conversational Agents flow builder and live preview" width="850"/>
</p>
<p align="center"><em>Fig. 1 — Flow builder (left) showing the Start Page → Ticket Information → Confirm Trip flow, alongside a live chat preview (right) of a full booking conversation from Austin to Boston.</em></p>

## 🗣️ Example Conversation

```
User:   I'd like to book a flight
Agent:  What city would you like the flight to depart from?
User:   Austin
Agent:  What is the month and day of the departure?
User:   Tomorrow
Agent:  What is your destination city?
User:   Boston
Agent:  Just to confirm — a flight from Austin to Boston, departing tomorrow. Shall I book it?
```

## 🛠️ Built With

- **Google Cloud Conversational Agents** — visual flow builder for designing conversational AI agents
- **Natural Language Understanding (NLU)** — intent detection and entity extraction for cities and dates
- **Built-in Preview Simulator** — used to test and validate the conversation in real time

## 🎯 Skills Demonstrated

- Designing multi-page conversational flows and page-to-page routing
- Structuring multi-turn dialogue to capture structured data (locations, dates) from free-form user input
- Configuring an agent's language settings and testing conversations live
- Applying foundational agentic AI / conversational design principles within the Google Cloud ecosystem

## ✅ Lab Completion

Completed the hands-on lab on Google Cloud Skills Boost with a final score of **100/100**.

<p align="center">
  <img src="assets/lab-completion.png" alt="Google Cloud Skills Boost lab completion score" width="700"/>
</p>
<p align="center"><em>Fig. 2 — Google Cloud Skills Boost lab: "Build a Basic Conversational Agent Flow," completed with a perfect score.</em></p>

## 🔑 Key Takeaway

This project strengthened my practical understanding of how conversational AI agents are structured behind the scenes — from intent detection, to guided data collection, to confirmation — using an enterprise-grade, no-code Google Cloud tool. It reflects hands-on experience with agentic AI design patterns that apply directly to building real-world customer-facing chatbots and virtual assistants.

## 📄 Reference

- Lab: *Build a Basic Conversational Agent Flow* — Google Cloud Skills Boost, "Agentic AI on Google Cloud" path

---

<p align="center"><b>Luxna Ramnauth</b></p>

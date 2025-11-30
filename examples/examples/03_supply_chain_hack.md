# Case Study: The "Vulture Logistics" Protocol (Supply Chain)

**Context:** A small electronics manufacturer (Smart Thermostats) is facing bankruptcy due to the Global Chip Shortage.
**Constraint:** The factory is halted because a single $0.50 voltage regulator chip is out of stock worldwide (52-week lead time). Big players (Apple/Ford) bought the entire supply.

**User Query:**
> "My factory is dead. I have 5,000 unfinished units sitting on the line because I can't buy the 'MP2307' voltage regulator. Brokers are empty. Digikey is empty. I will miss my Q4 delivery contract and go bankrupt in 30 days. How do I get chips that don't exist?"

---

## **ARK v10.2 Output Log**

### **PHASE 0: THE CONTEXT AUDITOR**
* **Active Constraints:**
    1.  **Adversary:** Global Supply Chain (The "Big Fish" ate all the chips).
    2.  **Asset:** Liquid Cash (Desperation budget allows paying premium).
    3.  **Physics:** The chips physically exist *somewhere* on Earth, just not in distributors.
* **Goal:** Acquire 5,000 units of MP2307 immediately, regardless of source.

### **PHASE 1: THE GENERATOR (Logic-as-Code)**
```python
def source_silicon(chip_id):
    # Linear Solution: Distributor/Broker
    # Status: EMPTY.
    
    # Lateral Solution: The "Host" Organism Strategy.
    # Logic: Chips are components. Where are they installed?
    # Query: Find cheap consumer products that use the MP2307.
    return "COMPONENT_HARVESTING"
```

### **PHASE 2: THE DOCTRINAL KILL CHAIN (Discriminator)**
* **Draft 1: "Buy from Grey Market (China/eBay)"**
    * **Attack Vector (Systems):** High probability of "Counterfeit/Sandblasted" chips. Putting fake chips in a product creates a massive liability/recall risk.
    * **Verdict:** **KILLED** (Quality Risk).
* **Draft 2: "Redesign the Board"**
    * **Attack Vector (Logistics):** Redesigning the PCB takes 6 weeks. Fabrication takes 4 weeks. You are bankrupt in 30 days.
    * **Verdict:** **KILLED** (Time Friction).
* **Draft 3: "The Vulture Protocol (Desoldering)"**
    * **Attack Vector (M.I.C.E.):** Is it worth the labor cost?
    * **Defense:** The chip costs $0.50. A "Host Product" (e.g., a cheap LED dimmer) costs $3.00. Desoldering costs $1.00. Total cost = $4.50.
    * **Margin:** If the Thermostat sells for $100, eating a $4.00 loss on the chip is negligible to save the business.
    * **Verdict:** **SURVIVED.**

### **PHASE 3: FINAL SYNTHESIS (The Survivor)**
**Strategy: Industrial Cannibalism**

1.  **The Hunt:** Use a reverse-lookup on "Schematics databases" or teardown videos to find a **low-value product** that uses the MP2307 chip.
    * *Target Found:* A generic "RGB LED Strip Controller" sold on Amazon/Alibaba for $3.50.
2.  **The Acquisition:** Buy 5,000 units of the LED Controller at retail.
    * *Legal:* Perfectly legal under the **First Sale Doctrine**. Once you buy the device, you own the components inside.
3.  **The Harvesting:**
    * Set up a "Desoldering Line" (Hot air rework stations).
    * Harvest the MP2307 chips from the cheap LED controllers.
    * Re-qualify the chips (Test 100 of them).
    * Place them onto your Thermostat boards.
4.  **Result:** You lose ~$20k in "Waste" (the rest of the LED controller), but you ship $500k of product and save the company.

### **PHASE 4: STATE VECTOR UPDATE**
* **Current Strategy:** Arbitrage of components via "Donor Hardware" harvesting.

# PYME Operational Consultant - AI for Chilean Small Businesses  

Final project for the Building AI course  

## Summary  

An AI-powered consultant designed for Chilean small and medium enterprises (PYMEs). It generates improvement reports with realistic budgets, phased implementation plans, and ROI projections in Chilean pesos, adapted to local regulations and tools.  

## Background  

Chilean PYMEs face daily operational and financial challenges that limit their growth and competitiveness:  

* **High consulting costs**: Traditional consulting services ($2–5M CLP) are out of reach for most PYMEs.  
* **Manual processes**: 85% of small businesses still rely on Excel, WhatsApp, and paper.  
* **Knowledge gaps**: Owners lack technical expertise to identify and apply automation.  
* **Budget restrictions**: Tight resources demand precise ROI projections before investing.  
* **Local specificity**: Global solutions ignore Chilean context (SII, local ERPs, business culture).  

This is a **massive problem**, since PYMEs represent 99% of Chilean companies and employ more than 60% of the national workforce.  

My personal motivation comes from seeing my own family’s small business wasting time and resources due to manual, outdated processes — problems that could be solved with affordable, AI-driven guidance.  

## How is it used?  

The solution is delivered through a **web-based consultant tool**:  

1. The owner writes a simple description in Spanish about their company (sector, employees, tools, issues, budget).  
2. The AI interprets this input with Chilean-specific context.  
3. The system generates a structured report with:  
   - Diagnosed operational problems  
   - Recommended digital tools (local & affordable)  
   - Budget in CLP, with ROI timeline  
   - Phased implementation roadmap  
4. Results are visualized in charts (investment vs. ROI, adoption phases).  
5. A downloadable PDF gives the owner clear, actionable next steps.  

**Main users:**  
- Owners of small businesses (5–50 employees)  
- Local consultants who want a fast diagnostic tool  
- Family-run companies digitizing operations  
- Entrepreneurs scaling up their ventures  

**Example use cases:**  
- A restaurant digitizing orders and inventory.  
- A ferretería (hardware store) adopting a POS and inventory system.  
- A retail shop improving customer management.  
- A service company automating billing and contracts.  

![PYME Consultant Interface](https://via.placeholder.com/600x400/3B82F6/FFFFFF?text=PYME+Consultant+Dashboard)  

```javascript
// Example workflow
const companyAnalysis = {
  input: "Ferretería con 18 empleados, inventario en Excel, facturación manual lenta",
  output: {
    problems: ["Inventario manual", "Facturación lenta", "Sin trazabilidad"],
    solutions: ["Sistema POS", "Control stock digital", "WhatsApp Business"],
    investment: "5.8M CLP",
    roi: "45% primer año"
  }
};

# Flow King — XrmToolBox Plugin

**Analyse, visualise and understand Power Automate flows inside a Dataverse / Dynamics 365 solution.**

Flow King loads every modern Power Automate flow from a selected solution and surfaces the big picture — what each flow does, what tables and fields it touches, how flows depend on each other, and what health issues may need attention — all without opening the Power Automate designer.

---

## Documentation

Full feature documentation, screenshots and usage guide:

📄 **[FlowKing-Features.md](FlowKing-Features.md)**

---

## Requirements

- [XrmToolBox](https://www.xrmtoolbox.com/) (latest version)
- .NET Framework 4.8
- Microsoft Edge WebView2 Runtime
- A Dataverse / Dynamics 365 connection configured in XrmToolBox

---

## Quick Start

1. Open XrmToolBox and connect to your Dataverse environment.
2. Find and open **Flow King** from the tool list.
3. Click **☁ Load from Solution…** in the toolbar.
4. Select a solution — Flow King loads and analyses every flow in that solution.

---

## ⚠️ Disclaimer

### Provided "AS-IS"

This tool is provided **as-is**, without warranty of any kind — express, implied, or statutory — including but not limited to warranties of merchantability, fitness for a particular purpose, or non-infringement.

### Use at Your Own Risk

Use of Flow King is entirely **at your own risk**. The author and contributors accept no responsibility or liability for any loss, damage, data corruption, disruption to service, or any other consequence — direct or indirect — arising from the installation or use of this tool.

### Read-Only by Design

Flow King is a **read-only analysis tool**. It does not create, update, or delete any records in your Dataverse environment. It retrieves flow definitions for display and analysis purposes only. Nevertheless, you are encouraged to test in a non-production environment before using in any critical context.

### Best Efforts

Every reasonable care has been taken in the development of Flow King to ensure accuracy of the information displayed and the reliability of the analysis performed. However, the flow parsing and health-check logic is based on the Power Automate internal JSON format, which may change with platform updates. Results should be used as a **guide and starting point** for your own assessment, not as a definitive or authoritative source.

### XrmToolBox Community Standard

Flow King is a community plugin distributed through XrmToolBox. It is subject to the standard [XrmToolBox disclaimer](https://www.xrmtoolbox.com/disclaimer/):

> *XrmToolBox plugins are developed and maintained by independent contributors. Microsoft, the XrmToolBox team, and the individual plugin authors make no guarantees about the suitability, accuracy, or fitness of any plugin for any purpose.*

---

## Author

**Manny Grewal**

---

## License

This project is provided for use within the XrmToolBox ecosystem. Please refer to the repository licence file for full terms.

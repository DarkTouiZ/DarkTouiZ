# Adisorn Parama

**Computer Engineering student and builder focused on embedded systems, FPGA/HDL design, data platforms, and applied machine learning.**

I enjoy turning technical ideas into working systems: from low-level digital logic in VHDL/Verilog to Python-based analytics tools, C data-structure projects, and full-stack applications. My work usually sits close to the boundary between hardware, software, and real-world data.

[![GitHub](https://img.shields.io/badge/GitHub-DarkTouiZ-181717?style=flat&logo=github)](https://github.com/DarkTouiZ)
[![Focus](https://img.shields.io/badge/Focus-FPGA%20%7C%20ML%20%7C%20Systems-blue)](#current-focus)
[![Code](https://img.shields.io/badge/Code-Python%20%7C%20C%20%7C%20Verilog%20%7C%20VHDL-green)](#technical-stack)

## Current Focus

- FPGA and digital design using **VHDL**, **Verilog**, testbenches, finite-state machines, datapaths, and simulation-driven verification.
- Applied machine learning for geospatial and urban analytics, including risk modeling, explainability, and dashboard delivery.
- Systems programming in C, especially graph algorithms, memory-oriented data structures, and database-style representations.
- Building practical applications that connect data, models, and user-facing tools.

## Featured Projects

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| [H-Spot App Service](https://github.com/DarkTouiZ/H-Spot-App-Service) | Spatio-temporal accident risk modeling for Bangkok with hotspot analysis, geospatial features, XAI, and an interactive dashboard. | Python, GeoPandas, XGBoost, SHAP, Streamlit, MLflow |
| [Player Intelligence System](https://github.com/DarkTouiZ/player-intelligence-system) | Player analytics system built around structured tasks and intelligence components. | Python, analytics workflow |
| [DBMS Represent by C](https://github.com/DarkTouiZ/DBMS-Represent-by-C) | Database-style graph representation with shortest path, BFS, and DFS functions implemented in C. | C, graph algorithms, data structures |
| [CPE223 Computer Architecture](https://github.com/DarkTouiZ/CPE223_Computer_Achitecture) | Computer architecture practice with digital logic, HDL concepts, and FPGA-oriented thinking. | VHDL, Verilog, computer architecture |
| [Game Aided for Learning Celestial Sphere VR](https://github.com/DarkTouiZ/Game-Aided-for-Learning-Celestial-Sphere-VR) | Learning-focused VR/game concept for celestial sphere education. | VR, interactive learning |

## HDL / FPGA Work

I am especially interested in how digital systems are designed, simulated, and mapped onto FPGA hardware. My HDL practice includes:

- Combinational and sequential logic design
- Finite-state machines and counters
- Register-transfer level design
- Testbench-based simulation
- Timing-aware FPGA implementation mindset
- VHDL and Verilog code organization for readable hardware modules

Example Verilog module:

```verilog
module counter_4bit (
    input  wire clk,
    input  wire rst_n,
    input  wire enable,
    output reg  [3:0] count
);
    always @(posedge clk or negedge rst_n) begin
        if (!rst_n)
            count <= 4'b0000;
        else if (enable)
            count <= count + 4'b0001;
    end
endmodule
```

Example VHDL process:

```vhdl
process(clk, rst_n)
begin
    if rst_n = '0' then
        q <= '0';
    elsif rising_edge(clk) then
        if enable = '1' then
            q <= d;
        end if;
    end if;
end process;
```

## Technical Stack

**Languages:** Python, C, Verilog, VHDL, JavaScript, SQL  
**Hardware / Digital:** FPGA design, RTL, FSMs, datapaths, computer architecture, simulation, testbenches  
**Data / ML:** XGBoost, Scikit-learn, SHAP, GeoPandas, Streamlit, MLflow  
**Software:** Git, Linux, API integration, data pipelines, dashboard development  
**Interests:** embedded systems, intelligent systems, geospatial analytics, digital logic, practical AI tools

## GitHub Snapshot

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=DarkTouiZ&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DarkTouiZ&layout=compact&theme=default&hide_border=true" alt="Top languages" />
</p>

## Contact

- GitHub: [@DarkTouiZ](https://github.com/DarkTouiZ)
- Email: [adisorn.safe01@gmail.com](mailto:adisorn.safe01@gmail.com)


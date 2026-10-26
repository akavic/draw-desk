# draw-desk

Draw Desk is a staff assistant for EuroMillions. Support staff ask how a prize tier works or whether a ticket won the latest draw. The assistant retrieves the answer from the rule documents or calls the live-draw tool, then returns a structured result. It refuses to predict future winning numbers.

The project includes a Gradio counter, a switch between GPT and a local model, a retrieval layer over the rules, an MCP server for the tools, and a 30-question scorecard that grades retrieval, answer match, and tool use. Docker, GitHub Actions, and a small AWS deployment package the service, with the lottery token stored in Secrets Manager.

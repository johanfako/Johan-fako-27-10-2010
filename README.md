# Zhrnutie najnovších trendov v informatike s licenciou MIT

# Licencia MIT
mit_licence = """
MIT License

Copyright (c) 2024 Johan Fako

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
"""

# Funkcia na zhrnutie trendov
def summarize_trends():
    trends = {
        "osmAG Map Comprehension with LLMs": "Pochopenie mapy pomocou veľkých jazykových modelov.",
        "COIN-LIO": "Detekcia neinformatívnych smerov v registrácii bodových mračien.",
        "LCB-net": "Zlepšenie automatického rozpoznávania reči s obohatenými textovými informáciami.",
        "NEPTUNE": "Plánovanie trajektórií pre viacero bezpilotných vozidiel."
    }
    
    for trend, description in trends.items():
        print(f"{trend}: {description}")

# Hlavný program
if __name__ == "__main__":
    print("Najnovšie trendy v informatike:")
    summarize_trends()
    print("\nLicencia MIT pre tento kód:")
    print(mit_licence)

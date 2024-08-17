# Hackathon-1-catalog

Transportation and logistics: 

Advanced E-Commerce:The integration of augumented reality technology in shopping malls aims to improve the traditional shopping experience by allowing shoppers to virtually try on clothing and accessories in real_time, offering accurate size and fit simulations, a diverse range of virtual products, and seamless integration with E-Commerce platforms.

GOAL OF THE PROJECT:Industry Innovation and Infrastructure
---------------------------------------------------------------------------- CODE FOR THE ABOVE SCENARIO-----------------------------------------------------------------------------------------------------

# Size and Fit Simulation to improve the sales:

def get_measurements():
    print("Please enter your measurements (in inches):")
    chest = float(input("Chest/Bust size: "))
    waist = float(input("Waist size: "))
    hips = float(input("Hips size: "))
    return chest, waist, hips
    
def suggest_size(chest, waist, hips):
    size_chart = {
        "XS": {"chest": (30, 32), "waist": (24, 26), "hips": (33, 35)},
        "S": {"chest": (33, 35), "waist": (27, 28), "hips": (36, 37)},
        "M": {"chest": (36, 38), "waist": (29, 31), "hips": (38, 40)},
        "L": {"chest": (39, 41), "waist": (32, 34), "hips": (41, 43)},
}
for size, ranges in size_chart.items():
        if (ranges['chest'][0] <= chest <= ranges['chest'][1] and
            ranges['waist'][0] <= waist <= ranges['waist'][1] and
            ranges['hips'][0] <= hips <= ranges['hips'][1]):
            return size
def main():
    print("Welcome to the Size and Fit Simulation!")
    chest, waist, hips = get_measurements()
    recommended_size = suggest_size(chest, waist, hips)
    if recommended_size !="Size not found.":
    print(f"\n Based on measurments:{recomended-size}")
    else:
    print(f"\n{recommended_size}")
    
if __name__ == "__main__":
    main()

[105ed49a-f88a-42d4-b13a-3fd9de799cf8](https://github.com/user-attachments/assets/8643e72a-083e-4b94-8c9b-fb11dd0e7f97)   -----------------OUTPUT SCREENSHOT TO IMPROVE THE SALES OF THE E-COMMERCE PLATFORM.



    
  

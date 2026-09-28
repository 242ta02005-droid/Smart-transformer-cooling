# Smart-transformer-cooling
# Smart Transformer Cooling System

LOW_TEMP = 40
MEDIUM_TEMP = 60
HIGH_TEMP = 80

print("==============================")
print("   SMART TRANSFORMER COOLING")
print("==============================")

temperature = float(input("Enter transformer temperature (°C): "))

print("\nTransformer Temperature:", temperature, "°C")

if temperature < LOW_TEMP:
    print("🟢 Temperature is LOW")
    print("❄️ Cooling Fan: OFF")

elif temperature < MEDIUM_TEMP:
    print("🟡 Temperature is MODERATE")
    print("🌀 Cooling Fan: LOW SPEED")

elif temperature < HIGH_TEMP:
    print("🟠 Temperature is HIGH")
    print("🌀 Cooling Fan: HIGH SPEED")

else:
    print("🔴 TEMPERATURE TOO HIGH")
    print("🌀 Cooling Fan: MAXIMUM SPEED")
    print("⚠️ Transformer protection alert!")

print("\nCooling system monitoring completed.")

# Energy Requirement Prediction

![9AGO-artigo-modelo-predição-de-consumo-de-energia_0](https://user-images.githubusercontent.com/50632051/206514420-67e9ebe0-dd76-4add-96dc-0aefaf5ce89f.png)

## Business Problem

Electrical utilities need to efficiently plan the allocation of generating units in their power plants to match their energy demand because if the demand is higher than the generation, it can cause several blackouts resulting in a huge loss to the economy. And, if the generation is higher than the demand the extra electricity will be wasted and it can also create an unnecessary load on the transmission lines.

Hence, it is important for the utilities to have a forecast of the energy consumption to be able to allocate appropriate resources to meet their demand. A month, week or day-ahead forecast can help the utilities plan for a larger time scale, but for smoother daily operations an hourly forecast can prove very useful. For example, if the plant operators get a high energy forecast for the next hour, they can ramp up the energy supply by switching on more power plants.

## Solution approach

Using 10 years' worth of hourly energy consumption data, we could try to learn from the trends and signals and build a model to effectively forecast energy consumption for a single day. The energy companies could utilize this model to better plan for future and in-return not only help the economy running but also reduce energy wastage.


## Forecasted power consumption for the next day

Used Facebook Prophet model with time-based features as the final model with 12% MAPE on test data and used it to generate the energy consumption prediction for the next day. 

<img width="961" alt="Screen Shot 2022-12-09 at 6 24 49 PM" src="https://user-images.githubusercontent.com/50632051/206811395-6bb0a783-40f5-4d20-a62c-d961ef9a147c.png">

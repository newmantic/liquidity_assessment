# liquidity_assessment

The Liquidity Assessment Model in fixed income markets is used to evaluate how liquidity affects bond prices. Liquidity refers to how easily an asset can be bought or sold in the market without significantly affecting its price. In bond markets, liquidity plays a crucial role in determining the price of a bond, especially for corporate bonds, municipal bonds, or other less liquid securities.


Liquidity Premium (L):
The additional yield required by investors to compensate for the lower liquidity of a bond. A less liquid bond typically trades at a higher yield (lower price) compared to a more liquid bond.

Market Yield (Y):
The yield required by the market for a bond without considering liquidity effects.
Liquidity-Adjusted Yield (Y_L):
The yield that incorporates the liquidity premium to reflect the true market conditions.

Bond Price (P):
The present value of the bond's cash flows, discounted at the market yield or liquidity-adjusted yield.


The liquidity premium 
L is often added to the market yield to account for liquidity risk:
Y_L = Y + L
Where:
Y is the market yield (excluding liquidity effects).
L is the liquidity premium.
Y_L is the liquidity-adjusted yield.

Bond Price Calculation
The price of a bond P can be calculated using the market yield or the liquidity-adjusted yield as follows:
P= ∑_{t=1}^{T} C/(1+Y_L)^t + F/(1+Y_L)^T
Where:
C is the annual coupon payment.
T is the number of years to maturity.
F is the face value of the bond.
Y_L is the liquidity-adjusted yield.

Liquidity Premiumis the additional yield added to the market yield to account for liquidity risk. Liquidity-Adjusted Yield is the yield that includes the liquidity premium, reflecting the true market value considering liquidity risk. Bond Price Calculation is thus the bond price calculated by discounting the bond's cash flows at the liquidity-adjusted yield. This model helps investors assess the fair value of bonds while accounting for liquidity risks, which is especially important in less liquid markets.

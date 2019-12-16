<table border="0">
  <tr>
    <td align="left" valign="middle">
    <h1>EFR32 Proprietary Application Examples</h1>
  </td>
  <td align="left" valign="middle">
    <a href="https://www.silabs.com/wireless/proprietary">
      <img src="http://pages.silabs.com/rs/634-SLU-379/images/WGX-transparent.png"  title="Silicon Labs Gecko and Wireless Gecko MCUs" alt="EFM32 32-bit Microcontrollers" width="250"/>
    </a>
  </td>
  </tr>
</table>

## Silicon Labs Proprietary ##

Silicon Labs EFR parts support the use of proprietary wireless protocols. Proprietary wireless allows for customizable physical protocols. Silicon Labs provides two ways to create proprietary wireless applications. The first is RAIL or Radio Abstraction Interface Layer. RAIL provides a common API to access the radio on supported parts. This API can be used to build fully customized network stacks from scratch. Second, there is Connect, which is a fully-featured stack that can be customized for an application's needs. While it does not provide the flexibility that RAIL provides, it comes with many features already implemented, like the ability to form star and extended star networks, security features, and 802.15.4 link layer compatibility.

## Submodules ##

-proprietary_connect
  - All proprietary examples based on the Connect stack.
-proprietary_rail
  - All proprietary examples based on the RAIL API.

## Supported Series 1 Devices ##
  - EFR32MG1
  - EFR32BG1
  - EFR32FG1
  - EFR32MG12
  - EFR32BG12
  - EFR32FG12
  - EFR32MG13
  - EFR32BG13
  - EFR32FG13
  - EFR32MG14
  - EFR32BG14
  - EFR32FG14
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

# Silicon Labs Proprietary #

Silicon Labs EFR parts support the use of proprietary wireless protocols. Proprietary wireless allows for customizable physical protocols. Silicon Labs provides two ways to create proprietary wireless applications. The first is RAIL or Radio Abstraction Interface Layer. RAIL provides a common API to access the radio on supported parts. This API can be used to build fully customized network stacks from scratch. Second, there is Connect, which is a fully-featured stack that can be customized for an application's needs. While it does not provide the flexibility that RAIL provides, it comes with many features already implemented, like the ability to form star and extended star networks, security features, and 802.15.4 link layer compatibility.

## Submodules ##

- proprietary\_connect
  - All proprietary examples based on the Connect stack.
- proprietary\_rail
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

## Documentation ##

Official RAIL documentation can be found at our [Developer Documentation](https://docs.silabs.com/rail/latest/) page.  
Official Connect Stack documentation can be found at our [Developer Documentation](https://docs.silabs.com/connect-stack/latest/) page.

## Reporting Bugs/Issues and Posting Questions and Comments ##

To report bugs in the Application Examples projects, please create a new "Issue" in the "Issues" section of this repo. Please reference the board, project, and source files associated with the bug, and reference line numbers. If you are proposing a fix, also include information on the proposed fix. Since these examples are provided as-is, there is no guarantee that these examples will be updated to fix these issues.

Questions and comments related to these examples should be made by creating a new "Issue" in the "Issues" section of this repo.

## Disclaimer ##

The Gecko SDK suite supports development with Silicon Labs IoT SoC. Unless otherwise specified in the specific directory, all examples are considered to be EXPERIMENTAL QUALITY which implies that the code provided in the repos has not been formally tested and is provided as-is.  It is not suitable for production environments.  In addition, this code will not be maintained and there may be no bug maintenance planned for these resources. Silicon Labs may update projects from time to time.

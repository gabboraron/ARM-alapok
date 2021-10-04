# ARM-alapok
ARM architektúra alapjai

Használt alaplap: [STM32F756ZG Nucleo-144](https://www.st.com/en/evaluation-tools/nucleo-f756zg.html)

![cortex A series vs cortex M series](https://gsasindia.com/wp-content/uploads/2020/09/Cortex-A-Cortex-R-Cortex-M.png)
## EA1
**A széria**
- 1 utasítást 1 órajel ciklus alatt tud végrehajtani

![](https://img.hexus.net/v2/events/armtechday2014/CortexB.png)

**ARM Cortex M0**
- 32 bit
- Neumann architectóra
- két állaotú pipeline
- alvó/csökkentett üzemmód
- hardware szorzó
- swd *serial wire debug*

**ARM Cortex M3**
- 32bit
- Harvard architektúra
- 32-bites szorzás/osztás
- teljesítődés figyelés
- 12 órajel hosszú megszakítás
- integrált sleep mode
- 240 megszakítás alatt engedélyezhető bárhol, és van szoftveres leállítás is, pl hibakezelésre

**ARM Cortex M4**
- dedikált memória a regisztereknek
- 

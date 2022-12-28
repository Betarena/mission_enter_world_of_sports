
### BETARENA INTERVIEW #010

> COPY: https://gist.github.com/migbash/6574372aaf597664fe60d4adc427b31f

```
npm create svelte@latest betarena-interview
```

`WEB-2`

- Develop a quick **countdown clock** with 
	- [ ] svelte/sveltekit and 
	- [ ] reactive functions and
	- [ ] **JS** methods [without major errors]
- **[EXTENSION]** make use of a **+page.ts** sveltekit endpoint feature to have make use of the **dynamic load method,** for extraction of a target number, such as, for example:
	- [ ] /countdown/[countdown-int] => **/10**, which should be passed down to the Countdownd component - to inform the Countdown to start from 10 seconds.
-   [EXTENSION] countdown clock to have a reset button
-   [EXTENSION] countdown clock to reset automatically when reaches 00:00.

---

`WEB-3`

```
FuQPph6G2JJR0i5HN7HYjMGIskwKtufR7HzzMeIF5s0NpkyjNy134cZr1VRdDKJz | Moralis API Key
0x1111111254EEB25477B68fb85Ed929f73A960582 | ✅ V5 1-inch Router Smart Contract
```

 - **[EXTENSION]** the countdown clock to:
	- [ ] Auto-update and get a target smart-contract transactions and **FILTER LARGE ARRAY** **OBJECT** data obtained from Moralis for:
		- [ ] the ones done in the last Y seconds (and) 
		- [ ] with a transaction value of greater than X 
		- [ ] using Moralis API.
- **[EXTENSION]** Display this auto-updated data under the countdown clock once it reaches 0, and every time it reaches 0 update the data (essentially a refreshing of the data).
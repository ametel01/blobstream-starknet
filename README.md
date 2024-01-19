<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<div align="center">
  <img style="margin-bottom: 3px" src="docs/images/blobstreamSnBanner.png" height="300" />


  [![Check Workflow Status](https://github.com/keep-starknet-strange/blobstream-sn/actions/workflows/check.yml/badge.svg)](https://github.com/keep-starknet-strange/blobstream-sn/actions/workflows/check.yml)
  [![Build Workflow Status](https://github.com/keep-starknet-strange/blobstream-sn/actions/workflows/build.yml/badge.svg)](https://github.com/keep-starknet-strange/blobstream-sn/actions/workflows/build.yml)

  [![Exploration_Team](https://img.shields.io/badge/Exploration_Team-29296E.svg?&style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iNDAiIHpvb21BbmRQYW49Im1hZ25pZnkiIHZpZXdCb3g9IjAgMCAzMCAzMCIgaGVpZ2h0PSI0MCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCIgeG1sbnM6dj0iaHR0cHM6Ly92ZWN0YS5pby9uYW5vIj48ZGVmcz48ZmlsdGVyIHg9IjAlIiB5PSIwJSIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgaWQ9IkEiPjxmZUNvbG9yTWF0cml4IHZhbHVlcz0iMCAwIDAgMCAxIDAgMCAwIDAgMSAwIDAgMCAwIDEgMCAwIDAgMSAwIiBjb2xvci1pbnRlcnBvbGF0aW9uLWZpbHRlcnM9InNSR0IiLz48L2ZpbHRlcj48ZmlsdGVyIHg9IjAlIiB5PSIwJSIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgaWQ9IkIiPjxmZUNvbG9yTWF0cml4IHZhbHVlcz0iMCAwIDAgMCAxIDAgMCAwIDAgMSAwIDAgMCAwIDEgMC4yMTI2IDAuNzE1MiAwLjA3MjIgMCAwIiBjb2xvci1pbnRlcnBvbGF0aW9uLWZpbHRlcnM9InNSR0IiLz48L2ZpbHRlcj48Y2xpcFBhdGggaWQ9IkMiPjxwYXRoIGQ9Ik0uNDg0IDBoMjkuMDMxdjI5SC40ODR6bTAgMCIgY2xpcC1ydWxlPSJub256ZXJvIi8+PC9jbGlwUGF0aD48bWFzayBpZD0iRCI+PGcgZmlsdGVyPSJ1cmwoI0EpIj48ZyBmaWx0ZXI9InVybCgjQikiIHRyYW5zZm9ybT0ibWF0cml4KDEuNDUxNjEzIDAgMCAxLjQ1MTYxMyAuNDgzODcgLjAwMDAwMikiPjxpbWFnZSB3aWR0aD0iMjAiIHhsaW5rOmhyZWY9ImRhdGE6aW1hZ2UvcG5nO2Jhc2U2NCxpVkJPUncwS0dnb0FBQUFOU1VoRVVnQUFBQlFBQUFBVUNBQUFBQUNvNGtMUkFBQUFBbUpMUjBRQS80ZVB6TDhBQUFFTFNVUkJWQmlWWlpHeFNnTkJGRVZQeGlHRVlRc0pFc1RPTDdDM2t2eUZyYVFUb242RFdGa3M0Mkpwa1NxVmxaK1NEN0JjVnJPcEpIR1puYmtXbTAzanF5NjNlT2R4M3VEa3h3QW1iWmRjTzVPQTVCalJUUzdsK3pqQzlWMEk4bDEyT01DUUs4UVlWRmpibDVhNVFwU0Ntak1NT0FOd3VnWm83ZWIyYXA0QU12QzdtMHBOa01wS3lpSERrVXQxcWFoNm9ZN205bHd0bmxiVFJ6VXhCbmxZS2tRRjFWTllLVWd4YUdrQXNPM1l3OTNhdHNrQVIrL0hseEhGd1Z2NmFMNHVURXoyWlliRGQwdS9KWlcxVk9ESUlKZXFVZ3FOcXRudUZUS2I0T0Z6TTN5bXRhbWQvSjV2SU9IQU1ObnR3ZmZZWG9nZEZ0MWhIbk93QkIydDZOWDFrcjE2bll3RzQrMy9kL3dCVTArdjhmNXlrYW9BQUFBQVNVVk9SSzVDWUlJPSIgaGVpZ2h0PSIyMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCIvPjwvZz48L2c+PC9tYXNrPjwvZGVmcz48ZyBjbGlwLXBhdGg9InVybCgjQykiPjxnIG1hc2s9InVybCgjRCkiPjxnIHRyYW5zZm9ybT0ibWF0cml4KDEuNDUxNjEzIDAgMCAxLjQ1MTYxMyAuNDgzODcgLjAwMDAwMikiPjxpbWFnZSB3aWR0aD0iMjAiIHhsaW5rOmhyZWY9ImRhdGE6aW1hZ2UvcG5nO2Jhc2U2NCxpVkJPUncwS0dnb0FBQUFOU1VoRVVnQUFBQlFBQUFBVUNBSUFBQUFDNjRwYUFBQUFCbUpMUjBRQS93RC9BUCtndmFlVEFBQUJ5a2xFUVZRNGpXVlV5M2FyTUF3Y2FVeG9UOXRsL3YvL2JsYVhwRTBCUGJvUU9LVFZDdVNaa1QyV0paa1Q4SUdudUFEblpibEhPQUJWbms2dmxYeUdUWktaZ0FQY1UzTkVSSVI3aWlpQXpGQVZWU1VWR0hlWUEyd0FBSXFVQ3N6RTNRR0lxQ29BUktoWmtBQklBa0FIYStuVUQ0RE1Cek1DRVZBRnFlN09yZElETFAwTHdEeC9BMWE3L1J0bVg4UHdQZ3d2UFZPNDJkMEFUTk0xUW80RTNYWG0yVVZlSTJ4ZDcyWUxNRmZsZnhIdlpuQjNVdWZaWDE1NDJFMGRPMGl0Wkdaa1loaEkzaVF6elQ2N3R3VlYzYzRNd014YWEwY3Q5MmhOaHVHdExjczlNN3REQUZUVnpJcS9MTjRhajB4VkFHb1dtWGVOOENPem9yVm01dTVCaWo3YjEvMlBjUDJqdXNYcHRCVmNGcy9jbG40SnFTb3pvL1I2OGZwMkQxSmJvN3QxUUY5U3BXVG11bjZhSmFsSHBwbVJUZmFMS3hkL0dhYkFSVlZGa0xuVnpVUkV0UFpnQXFoYkxDWkpWUVV1MVdHem1XUjZoR2ZLdXNZNFBqbThGOC9yOWV0OFByc2I2Y0Q0MUo3citqM1AvMCtuajc5TUFPNnB5bkY4dE9jVHVlSit2OVcrOW12djV0WERQcmk5YWV6bmN6ZVM3cHYvblNrQ0VmNENWOTk1cjAvV2t4U3pLT255VmxYSi9teTMrYUhBZEJnakFFYnlOZ3h2Skd1a2tCeUdOL0oyR0NNQUNFdy9EU2xMWS8wb1VrZ0FBQUFBU1VWT1JLNUNZSUk9IiBoZWlnaHQ9IjIwIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJ4TWlkWU1pZCBtZWV0Ii8+PC9nPjwvZz48L2c+PC9zdmc+)](https://github.com/keep-starknet-strange)


</div>

## Overview

`blobstream-sn` is a port of Celestia Blobstream [contracts](https://github.com/celestiaorg/blobstream-contracts) 
in [Cairo](https://book.cairo-lang.org/) for [Starknet](https://starknet.io/).

## Build

To build the project, run:

```bash
scarb build
```

## Test

To test the project, run:

```bash
snforge
```

##

<div align="center">
  <b>We live on contributions, follow the guide <a href="CONTRIBUTING.md">here</a>!</b>
</div>

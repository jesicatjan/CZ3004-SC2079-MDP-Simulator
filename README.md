<br />
<p align="center">
  <h1 align="center">
    SC2079 Group 31 Multidisciplinary Project - Algorithm Simulator
  </h1>
</p>

## Setup

```bash
npm install
```

Start the app by

```bash
npm run dev
```

The simulator app will run at `localhost:3000`.

## Usage

The algorithm API server should be running at a specific address, which you will need to change in `BaseAPI.js` line 19, the default server address now is `localhost:5000`.

<div style="text-align:center"><img src="/images/Simulator.png" alt="Interface" width=350 ></div>

The interface is as intuitive as it can get. Position the robot where you want it to be and click on the buttons to add obstacles. Then click on `Submit` to find the path, or `Reset All` to clear the map and put the robot back to the starting position. `Reset Robot` just resets the robot to the starting position without clearing the map.

## Acknowledgements

We used [our seniors'](https://github.com/pyesonekyaw/CZ3004-SC2079-MDP-Simulator) simulator as a boilerplate to make some adjustments according to our group's needs.
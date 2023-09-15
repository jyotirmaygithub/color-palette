
import React, { useState } from "react";
import Mainbranch from "./components/Main";
import Values from "values.js";
import Plate from "./components/colorplate.png"

function App() {
  const [color, setColor] = useState('');
  const [list, setList] = useState(new Values("#008000").all())
  // const [alert,setAlert] = useState(null)

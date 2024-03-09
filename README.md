import React, {useEffect, useState} from "react";
import './index.css'

const Title = ({ text }) =>{
    return <h1>{text}</h1>;
}
const Header = () => {
    return (
        <div>
            <Title text="Header text"/>
        </div>
    )
}

const Content = ()=>{
    return(
        <div>
            <Title text="Content text" />
        </div>
    )
}
const Footer = ()=>{
    return(
        <div>
            <Title text="Footer text" />
        </div>
    )
}



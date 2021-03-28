# React-CreateStudent
CreateStudent

import React, { Component } from 'react'
import Form from 'react-bootstrap/Form'
import Button from 'react-bootstrap/Button'

export default class Createstudent extends Component {
    render() {
        return (
            <div className="form-wrapper">
                <h1> Create Student </h1>
                <Form>
                    <Form.Group controlId="Name">
                        <Form.Label>Name</From.Label>
                        <Form.Control type="text" />
                    </Form.Group> 

                    <Form.Group controlId="Email">
                        <Form.Label>Email</From.Label>
                        <Form.Control type="email" />
                    </Form.Group> 

                    <Form.Group controlId="Roll">
                        <Form.Label>Roll No.</From.Label>
                        <Form.Control type="text" />
                    </Form.Group> 

                    <Button variant="success" size="lg" block="block" type="submit">
                        Create Student
                    </Button>      
                </Form>
            </div>
        )
    }
}

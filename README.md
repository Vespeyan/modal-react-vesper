## Instructions to use this package

### Import the package in your project

<code>

    import { Modal } from "modal-react-vesper";

</code>

### Define a state and a function to modify it

<code>

    const [isShowing, setIsShowing] = useState(false);

</code>

### Call the component where you want it without forgetting to set his attributes

<code>

    <Modal isShowing={isShowing} close={() => setIsShowing(false)}/>

</code>

You can set the `isShowing` state whenever you want to display or hide the modal
# Button Black
```
<TouchableHighlight
  style={[ styles.btnBuscar, estiloAnimacion] } >
     <Text style={styles.textoBuscar } >Buscar Clima</Text>
</TouchableHighlight>
```
   
```
const styles = StyleSheet.create({
    btnBuscar: {
        marginTop: 50,
        backgroundColor: '#000',
        padding: 10,
        justifyContent: 'center'
    },
    textoBuscar: {
        color: '#FFF',
        fontWeight: 'bold',
        textTransform: 'uppercase',
        textAlign: 'center',
        fontSize: 18
    }
})
```

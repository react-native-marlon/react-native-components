# Form
```
const styles = StyleSheet.create({
  app: {
    flex: 1,
    justifyContent: 'center'
  },
  contenido: {
    marginHorizontal: '2.5%'
  }
});
```


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

#  TextInput
```
<View>
  <TextInput 
     value={ciudad}
     style={styles.input}
     onChangeText={ ciudad => guardarBusqueda({ ...busqueda, ciudad }) }
     placeholder="Ciudad"
     placeholderTextColor="#666"
  />
</View>
```
```
input: {
        padding: 10,
        height: 50,
        backgroundColor: '#FFF',
        fontSize: 20,
        marginBottom: 20,
        textAlign: 'center'
    },
    
```


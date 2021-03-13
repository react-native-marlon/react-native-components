# Button Black
```
<TouchableWithoutFeedback
                    onPressIn={ () => animacionEntrada() }
                    onPressOut={ () => animacionSalida()  }
                    onPress={ () => consultarClima() }
                >
                    <Animated.View
                        style={[ styles.btnBuscar, estiloAnimacion] }
                    >
                        <Text style={styles.textoBuscar } >Buscar Clima</Text>
                    </Animated.View>
                </TouchableWithoutFeedback>
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

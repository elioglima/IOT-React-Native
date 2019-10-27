# IOT - REACT NATIVE

### Internet of Things - Light Off/On

    Este projeto é destinado ao aprendiasado das funcionabilidades disponiveis para visual do react native.

    pakages: REDUX, REDUX-SAGA, REDUCER
    sistemas: WINDOWS 10, MAC-OS

    Pontos abordado:

# Ambiente de execução:

    - IOS
    - Android

# Comandos utilizados

    create-react-native-app nomedoapp
    react-native upgrade
    react-native run-android

# Problemas de instalação e Soluções

    reopen android studio as admin. build the gradle. if no issue, proceed on
    access the android folder of your app. i.e c:\folder\app\android
    type in gradlew clean
    run react-native run-android

    macos
    * criar em /android/local.properties
    * /Users/elio.lima/Library/Android/sdk

    1-> Go to your React-native Project -> Android
    2-> Create a file local.properties
    3-> Open the file
    4-> paste your Android SDK path like below

    5-> in Windows sdk.dir = C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk
    5-> in macOS sdk.dir = /Users/USERNAME/Library/Android/sdk
    5-> in linux sdk.dir = /home/USERNAME/Android/Sdk
    obs: Replace USERNAME with your user name

    7-> Now, Run the react-native run-android in your terminal.

# Sobre o IOT

    1) git clone https://github.com/elioglima/IOT.git
    2) yarn - necessario para instalar os pacotes
    3) react-native run-android ou yarn android - para executar no emulador

# Estilização

é necessário instalar o plugin de viewport para trabalhar dentro do StyleSheet

        1) npm install react-native-viewport-units --save

        var styles = StyleSheet.create({
        lookingGood: {
            width: 15*vmin,
            height: 10*vmax,
            padding: 2*vw,
            margin: 4*vh,
        }
        });

# Packages

        yarn add react-navigation
        yarn add react-native-gesture-handler
        react-native link react-native-gesture-handler

        npm install redux react-redux connected-react-router react-router
        yarn add redux react-redux connected-react-router react-router



<svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="475.085px" height="475.085px" viewBox="0 0 475.085 475.085" style="enable-background:new 0 0 475.085 475.085;"
	 xml:space="preserve"	 
	 >

<g>
	<g>
		<path d="M237.545,255.816c9.899,0,18.468-3.609,25.696-10.848c7.23-7.229,10.854-15.799,10.854-25.694V36.547
			c0-9.9-3.62-18.464-10.854-25.693C256.014,3.617,247.444,0,237.545,0c-9.9,0-18.464,3.621-25.697,10.854
			c-7.233,7.229-10.85,15.797-10.85,25.693v182.728c0,9.895,3.617,18.464,10.85,25.694
			C219.081,252.207,227.648,255.816,237.545,255.816z"
			fill="#000"
			/>
		<path d="M433.836,157.887c-15.325-30.642-36.878-56.339-64.666-77.084c-7.994-6.09-17.035-8.47-27.123-7.139
			c-10.089,1.333-18.083,6.091-23.983,14.273c-6.091,7.993-8.418,16.986-6.994,26.979c1.423,9.998,6.139,18.037,14.133,24.128
			c18.645,14.084,33.072,31.312,43.25,51.678c10.184,20.364,15.27,42.065,15.27,65.091c0,19.801-3.854,38.688-11.561,56.678
			c-7.706,17.987-18.13,33.544-31.265,46.679c-13.135,13.131-28.688,23.551-46.678,31.261c-17.987,7.71-36.878,11.57-56.673,11.57
			c-19.792,0-38.684-3.86-56.671-11.57c-17.989-7.71-33.547-18.13-46.682-31.261c-13.129-13.135-23.551-28.691-31.261-46.679
			c-7.708-17.99-11.563-36.877-11.563-56.678c0-23.026,5.092-44.724,15.274-65.091c10.183-20.364,24.601-37.591,43.253-51.678
			c7.994-6.095,12.703-14.133,14.133-24.128c1.427-9.989-0.903-18.986-6.995-26.979c-5.901-8.182-13.844-12.941-23.839-14.273
			c-9.994-1.332-19.085,1.049-27.268,7.139c-27.792,20.745-49.344,46.442-64.669,77.084c-15.324,30.646-22.983,63.288-22.983,97.927
			c0,29.697,5.806,58.054,17.415,85.082c11.613,27.028,27.218,50.34,46.826,69.948c19.602,19.603,42.919,35.215,69.949,46.815
			c27.028,11.615,55.388,17.426,85.08,17.426c29.693,0,58.052-5.811,85.081-17.426c27.031-11.604,50.347-27.213,69.952-46.815
			c19.602-19.602,35.207-42.92,46.818-69.948s17.412-55.392,17.412-85.082C456.809,221.174,449.16,188.532,433.836,157.887z"
			fill="#000"
			/>
	</g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
</svg>

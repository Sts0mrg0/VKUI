```jsx
  <View header activePanel="header">
    <ScrollView header={{ title: 'Header' }} id="header" theme="white">
      <Header>
        Плейлисты
      </Header>
      <Header level="2">
        Импорт друзей
      </Header>
      <Header level="2" aside={<span style={{ color: colors.accentBlue }}>Показать все</span>}>
        Приглашения
      </Header>
    </ScrollView>
  </View>
```
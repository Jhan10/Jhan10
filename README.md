## Hi there 👋

<!--
**Jhan10/Jhan10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
 <LexicalComposer
         initialConfig={{
            namespace: "MyEditor",
            theme,
            editable: editable,
            nodes: nodeDependencies,
            onError,
         }}
      >
         <StyledRoot onMouseOver={handleOnMouseOverRoot} onMouseLeave={handleOnMouseLeaveRoot}>
            <RichTextPlugin
               contentEditable={<ContentEditable />}
               placeholder={<div>{placeholder || "Enter some text..."}</div>}
               ErrorBoundary={LexicalErrorBoundary}
            />
         </StyledRoot>

<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="239ccf91-13f2-425e-afec-a80545d5889e"
    v-bind:style="{'width':'100%','height':'auto'}">
    <Form v-bind:snapX="false" v-bind:snapY="false" v-bind:isLock="false" bgColor="" ncBgType="bgColor"
      position="relative" v-bind:poweredBy="true" v-bind:slideStep="true"
      v-bind:tabRawData="[{'id':'20001124144305863u9BeGxKvUBzsPbOFQDz','name':'Slide 1','delay':0,'repeat':1,'children':['d2d17be9-8318-4480-8ac7-053f01aca486'],'duration':1,'animation':''},{'id':'b5e27665-b001-4442-bb55-54402a1b830f','name':'Slide2','children':['06509479-d6ec-491b-a3da-1b5894a4f849'],'animation':'','duration':1,'delay':0,'repeat':1},{'id':'a7199d28-8610-4f31-96af-e3905df07c9a','name':'Slide3','children':[],'animation':'','duration':1,'delay':0,'repeat':1}]"
      v-bind:progressBar="true" v-bind:currentIndex="2" ncTooltipText="" progressBarColor="#0F0F0F40"
      id="04b8e03b-4c63-46b1-8a81-6fcacc92f0e7"
      v-bind:style="{'width':'100%','height':'100%','zIndex':2,'tabIndex':'-1','boxShadow':'','marginTop':'0px','background':'','marginLeft':'0px','paddingTop':'','visibility':'visible','borderColor':'#c7c7c7','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}">
      <WDangerButton tag="button" href="" v-bind:pill="false" size="md" text="Danger" type="button" v-bind:block="false"
        color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="danger"
        v-bind:isEnabled="true" background="#dc3545" linkTarget="_top" ncLinkType="link" borderColor="#dc3545"
        v-bind:resetTrigger="false" animationName="" ncTooltipText="" verticalWidth="60px" formTransition="none"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#dc3545"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545"
        ncHoverBackgroundColor="#dc3545" ncDisableBackgroundColor="#969696" position="relative"
        id="d2d17be9-8318-4480-8ac7-053f01aca486"
        v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'0px','paddingLeft':'','wordSpacing':'0px','marginBottom':'0px','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':4}"/>
      <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
        color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="primary"
        ncBgType="bgColor" v-bind:isEnabled="true" background="#007bff" linkTarget="_top" ncLinkType="link"
        borderColor="#007bff" v-bind:resetTrigger="false" animationName="" ncTooltipText="" verticalWidth="60px"
        formTransition="none"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
        ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
        ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
        position="relative" v-bind:snapX="false" v-bind:snapY="false" id="06509479-d6ec-491b-a3da-1b5894a4f849"
        v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'','paddingLeft':'','wordSpacing':'0px','marginBottom':'','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':5}"/>
    </Form>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@import 'src/assets/styles/scroll';
 @include custom-scroll();
@media (min-width: 1024.05px){
[id='239ccf91-13f2-425e-afec-a80545d5889e'] {
             display: grid; 
             grid-template-columns: 0 100rem 0;
             grid-template-rows: 0 100vh 0;
          }
[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7']{
          grid-area: 2/2/3/3;
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='1']{
             display: grid; 
             grid-template-columns: 56.3671875rem 5.3125rem 38.3203125rem;
             grid-template-rows: minmax(50.15625rem, max-content) minmax(2.421875rem, max-content) minmax(3.671875rem, max-content);
          }
[id='06509479-d6ec-491b-a3da-1b5894a4f849']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='0']{
             display: grid; 
             grid-template-columns: 44.7265625rem 5.46875rem 49.8046875rem;
             grid-template-rows: minmax(28.671875rem, max-content) minmax(2.421875rem, max-content) minmax(25.15625rem, max-content);
          }
[id='d2d17be9-8318-4480-8ac7-053f01aca486']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='239ccf91-13f2-425e-afec-a80545d5889e'] {
             display: grid; 
             grid-template-columns: 0 100rem 0;
             grid-template-rows: 0 100vh 0;
          }
[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7']{
          grid-area: 2/2/3/3;
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='1']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 3.125rem 87.5rem 3.125rem;
             grid-template-rows: minmax(47.021484375rem, max-content) minmax(2.2705078125rem, max-content) minmax(3.4423828125rem, max-content);
          }
[id='06509479-d6ec-491b-a3da-1b5894a4f849']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),15.441176470588234rem);
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='0']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 3.125rem 87.5rem 3.125rem;
             grid-template-rows: minmax(26.8798828125rem, max-content) minmax(2.2705078125rem, max-content) minmax(23.583984375rem, max-content);
          }
[id='d2d17be9-8318-4480-8ac7-053f01aca486']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),15rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='239ccf91-13f2-425e-afec-a80545d5889e'] {
             display: grid; 
             grid-template-columns: 0 100rem 0;
             grid-template-rows: 0 100vh 0;
          }
[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7']{
          grid-area: 2/2/3/3;
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='1']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 4.166666667rem 83.333333332rem 4.166666667rem;
             grid-template-rows: minmax(45.976562499665626rem, max-content) minmax(2.2200520833171873rem, max-content) minmax(3.36588541664219rem, max-content);
          }
[id='06509479-d6ec-491b-a3da-1b5894a4f849']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),14.705882352705881rem);
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='0']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 4.166666667rem 83.333333332rem 4.166666667rem;
             grid-template-rows: minmax(26.28255208314219rem, max-content) minmax(2.2200520833171873rem, max-content) minmax(23.059895833165623rem, max-content);
          }
[id='d2d17be9-8318-4480-8ac7-053f01aca486']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),14.285714285485712rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='239ccf91-13f2-425e-afec-a80545d5889e'] {
             display: grid; 
             grid-template-columns: 0 100rem 0;
             grid-template-rows: 0 100vh 0;
          }
[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7']{
          grid-area: 2/2/3/3;
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='1']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 5rem 80rem 5rem;
             grid-template-rows: minmax(45.14062499999999rem, max-content) minmax(2.1796874999999996rem, max-content) minmax(3.3046874999999964rem, max-content);
          }
[id='06509479-d6ec-491b-a3da-1b5894a4f849']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),14.11764705882353rem);
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='0']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 5rem 80rem 5rem;
             grid-template-rows: minmax(25.804687499999996rem, max-content) minmax(2.1796874999999996rem, max-content) minmax(22.640625rem, max-content);
          }
[id='d2d17be9-8318-4480-8ac7-053f01aca486']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),13.714285714285715rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='239ccf91-13f2-425e-afec-a80545d5889e'] {
             display: grid; 
             grid-template-columns: 0 100rem 0;
             grid-template-rows: 0 100vh 0;
          }
[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7']{
          grid-area: 2/2/3/3;
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='1']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 6.4rem 74.4rem 6.4rem;
             grid-template-rows: minmax(43.73625rem, max-content) minmax(2.1118750000000004rem, max-content) minmax(3.201875rem, max-content);
          }
[id='06509479-d6ec-491b-a3da-1b5894a4f849']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),13.129411764705885rem);
          }[id='04b8e03b-4c63-46b1-8a81-6fcacc92f0e7'] /deep/ > [id='0']{
        justify-content: center;
 align-content: center;
             display: grid; 
             grid-template-columns: 6.4rem 74.4rem 6.4rem;
             grid-template-rows: minmax(25.001875000000002rem, max-content) minmax(2.1118750000000004rem, max-content) minmax(21.936250000000005rem, max-content);
          }
[id='d2d17be9-8318-4480-8ac7-053f01aca486']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),12.754285714285714rem);
          }
}
</style>
class Info
  include Capybara::DSL

  def get_info
    @inf = {
      #pega a informação do elemento e extrai o texto
      value: find(:xpath, "//*AQUI VAI O XPATH DO ELEMENTO").text,
    }
  end

  def show_info
    return @inf[:value]
  end
end

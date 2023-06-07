/* About */

	.about-info {
		padding: 7rem 0;
		position: relative;
	}

		.about-info > .inner {
			display: -moz-flex;
			display: -webkit-flex;
			display: -ms-flex;
			display: flex;
			-moz-align-items: center;
			-webkit-align-items: center;
			-ms-align-items: center;
			align-items: center;
			-moz-justify-content: space-between;
			-webkit-justify-content: space-between;
			-ms-justify-content: space-between;
			justify-content: space-between;
			margin: 0 auto;
			max-width: 75rem;
			width: calc(100% - 4rem);
		}

		.about-info h2 {
			-moz-transition: opacity 0.5s ease-out, -moz-transform 0.5s ease-out;
			-webkit-transition: opacity 0.5s ease-out, -webkit-transform 0.5s ease-out;
			-ms-transition: opacity 0.5s ease-out, -ms-transform 0.5s ease-out;
			transition: opacity 0.5s ease-out, transform 0.5s ease-out;
			margin-bottom: 0;
            font-weight: normal;
		}
        .about-info h3 {
            font-weight: normal;
        }

		.about-info .image {
			border-radius: 0;
			height: 100%;
			position: absolute;
			top: 0;
			width: 45%;
		}

			.about-info .image img {
				-moz-object-fit: cover;
				-webkit-object-fit: cover;
				-ms-object-fit: cover;
				object-fit: cover;
				border-radius: 0;
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
			}

		.about-info .content {
			padding: 5rem 5rem 2.5rem 5rem ;
			-moz-transition: opacity 0.5s ease-out, -moz-transform 0.5s ease-out;
			-webkit-transition: opacity 0.5s ease-out, -webkit-transform 0.5s ease-out;
			-ms-transition: opacity 0.5s ease-out, -ms-transform 0.5s ease-out;
			transition: opacity 0.5s ease-out, transform 0.5s ease-out;
			background-color: #fff;
			border-radius: 4px;
			position: relative;
			z-index: 1;
			width: 55%;
		}

		.about-info.odd .image {
			right: 0;
		}

		.about-info.even > .inner {
			-moz-flex-direction: row-reverse;
			-webkit-flex-direction: row-reverse;
			-ms-flex-direction: row-reverse;
			flex-direction: row-reverse;
		}

		.about-info.even .image {
			left: 0;
		}

		.about-info.accent1 {
			background-color: #7d5aa3;
		}

			.about-info.accent1 h2 {
				color: #ffffff;
			}

		.about-info.accent2 {
			background-color: #6e9ff0;
		}

			.about-info.accent2 h2 {
				color: #ffffff;
			}

		.about-info.accent3 {
			background-color: #5eb6df;
		}

			.about-info.accent3 h2 {
				color: #ffffff;
			}

		.about-info.accent4 {
			background-color: #67cfc9;
		}

			.about-info.accent4 h2 {
				color: #ffffff;
			}

		.about-info.is-inactive h2 {
			-moz-transform: translateY(-2rem);
			-webkit-transform: translateY(-2rem);
			-ms-transform: translateY(-2rem);
			transform: translateY(-2rem);
			opacity: 0;
		}

		.about-info.is-inactive .content {
			-moz-transform: translateY(2rem);
			-webkit-transform: translateY(2rem);
			-ms-transform: translateY(2rem);
			transform: translateY(2rem);
			opacity: 0;
		}

		@media screen and (max-width: 1280px) {

			.about-info {
				padding: 5.5rem 0;
			}

				.about-info > .inner {
					-moz-justify-content: -moz-flex-start;
					-webkit-justify-content: -webkit-flex-start;
					-ms-justify-content: -ms-flex-start;
					justify-content: flex-start;
				}

				.about-info h2 {
					padding: 0 3rem;
					width: 40%;
					text-align: center;
				}

				.about-info .content {
					padding: 4rem 4rem 1.5rem 4rem ;
					width: 45%;
				}

		}

		@media screen and (max-width: 980px) {

			.about-info {
				padding: 0;
				text-align: center;
			}

				.about-info > .inner {
					display: block;
					max-width: none;
					width: 100%;
				}

				.about-info h2 {
					padding: 2.5rem 2.5rem;
					width: 100%;
				}

					.about-info h2 br {
						display: none;
					}

				.about-info ul.actions {
					-moz-justify-content: center;
					-webkit-justify-content: center;
					-ms-justify-content: center;
					justify-content: center;
					width: 100%;
					margin-left: 0;
				}

					.about-info ul.actions li:first-child {
						padding-left: 0;
					}

				.about-info .image {
					display: block;
					height: 40vh;
					min-height: 20rem;
					width: 100%;
					position: relative;
				}

				.about-info .content {
					padding: 3rem 2.5rem 0.5rem 2.5rem ;
					border-radius: 0;
					width: 100%;
				}

					.about-info .content h3 br {
						display: none;
					}

				.about-info.is-inactive h2 {
					-moz-transform: none;
					-webkit-transform: none;
					-ms-transform: none;
					transform: none;
					opacity: 0;
				}

				.about-info.is-inactive .content {
					-moz-transform: none;
					-webkit-transform: none;
					-ms-transform: none;
					transform: none;
					opacity: 0;
				}

		}

        @media screen and (min-width: 980px) {

            .spotlight h2 {
                display: none;
            }
        }

        @media screen and (max-width: 980px) {

            .spotlight h3 {
                display: none;
            }
        }

		@media screen and (max-width: 736px) {

			.about-info h2 {
				padding: 1.5rem;
			}

			.about-info .content {
				padding: 2rem 1.5rem 0.1rem 1.5rem ;
			}

		}


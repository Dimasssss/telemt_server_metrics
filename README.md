# Server Metrics 2026-03-04 16:50:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 70773.4 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371443
telemt_connections_bad_total 19456
telemt_handshake_timeouts_total 23165
telemt_upstream_connect_attempt_total 41748
telemt_upstream_connect_success_total 41561
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 41561
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 9216
telemt_me_reconnect_success_total 9146
telemt_me_reader_eof_total 9469
telemt_me_idle_close_by_peer_total 9468
telemt_me_route_drop_no_conn_total 543678
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 275
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2991
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2045
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 1022
telemt_pool_swap_total 18
telemt_pool_force_close_total 792
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 9470
telemt_me_writer_restored_same_endpoint_total 9124
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 1120714
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 14869823264 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 374710882604 (348.98 GB)
telemt_user_unique_ips_current{user="hello"} 104
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 70769.9 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525787
telemt_connections_bad_total 6514
telemt_handshake_timeouts_total 30825
telemt_upstream_connect_attempt_total 125058
telemt_upstream_connect_success_total 123224
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 123218
telemt_upstream_connect_attempts_per_request{bucket="2"} 885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_timeout_total 1643
telemt_me_reconnect_attempts_total 67798
telemt_me_reconnect_success_total 67691
telemt_me_reader_eof_total 69430
telemt_me_idle_close_by_peer_total 69429
telemt_me_route_drop_no_conn_total 221944
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 296
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1331
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 190
telemt_me_writer_removed_unexpected_total 69510
telemt_me_writer_restored_same_endpoint_total 67665
telemt_me_writer_removed_unexpected_minus_restored_total 1845
telemt_user_connections_total{user="hello"} 421902
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 6248883348 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 132686716784 (123.57 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 70768.7 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1053670
telemt_connections_bad_total 209500
telemt_handshake_timeouts_total 30441
telemt_upstream_connect_attempt_total 91223
telemt_upstream_connect_success_total 90583
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 90582
telemt_upstream_connect_attempts_per_request{bucket="2"} 311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 40323
telemt_me_reconnect_success_total 40214
telemt_me_reader_eof_total 42339
telemt_me_idle_close_by_peer_total 42334
telemt_me_route_drop_no_conn_total 390366
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2203
telemt_desync_full_logged_total 732
telemt_desync_suppressed_total 1471
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 835
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42352
telemt_me_writer_restored_same_endpoint_total 40192
telemt_me_writer_removed_unexpected_minus_restored_total 2160
telemt_user_connections_total{user="hello"} 764127
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 14718007884 (13.71 GB)
telemt_user_octets_to_client{user="hello"} 263698064216 (245.59 GB)
telemt_user_unique_ips_current{user="hello"} 69
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 17446.1 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284935
telemt_connections_bad_total 34339
telemt_handshake_timeouts_total 6622
telemt_upstream_connect_attempt_total 6876
telemt_upstream_connect_success_total 6876
telemt_upstream_connect_attempts_per_request{bucket="1"} 6876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3030
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 903
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 97116
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 309
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 234184
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 2937687624 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 86820667320 (80.86 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 17805.5 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303279
telemt_connections_bad_total 3078
telemt_handshake_timeouts_total 4188
telemt_upstream_connect_attempt_total 8687
telemt_upstream_connect_success_total 8644
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8644
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 1412
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1443
telemt_me_route_drop_no_conn_total 122388
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 566
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_restored_same_endpoint_total 1394
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 263072
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 4301033496 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 78209046820 (72.84 GB)
telemt_user_unique_ips_current{user="hello"} 57
```
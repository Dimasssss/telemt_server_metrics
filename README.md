# Server Metrics 2026-03-07 02:07:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 28758.4 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327257
telemt_connections_bad_total 3885
telemt_handshake_timeouts_total 9590
telemt_upstream_connect_attempt_total 93969
telemt_upstream_connect_success_total 91220
telemt_upstream_connect_fail_total 2608
telemt_upstream_connect_attempts_per_request{bucket="1"} 93828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2608
telemt_me_keepalive_timeout_total 1936
telemt_me_reconnect_attempts_total 58428
telemt_me_reconnect_success_total 55906
telemt_me_reader_eof_total 58032
telemt_me_idle_close_by_peer_total 58030
telemt_me_route_drop_no_conn_total 122971
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1101
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 799
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 302
telemt_pool_swap_total 14
telemt_pool_force_close_total 627
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 58145
telemt_me_writer_restored_same_endpoint_total 55747
telemt_me_writer_restored_fallback_total 153
telemt_me_async_recovery_trigger_total 50521
telemt_me_writer_removed_unexpected_minus_restored_total 2245
telemt_user_connections_total{user="hello"} 297778
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 4430570560 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 128793263844 (119.95 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 28758.4 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142975
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 18889
telemt_upstream_connect_attempt_total 193524
telemt_upstream_connect_success_total 193522
telemt_upstream_connect_attempts_per_request{bucket="1"} 193522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1504
telemt_me_reconnect_attempts_total 151946
telemt_me_reconnect_success_total 151517
telemt_me_reader_eof_total 137504
telemt_me_idle_close_by_peer_total 137499
telemt_me_route_drop_no_conn_total 44290
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 835
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 21
telemt_pool_force_close_total 1379
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 137546
telemt_me_writer_restored_same_endpoint_total 151515
telemt_me_async_recovery_trigger_total 50514
telemt_user_connections_total{user="hello"} 116947
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1595546568 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 39238333680 (36.54 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 28758.4 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255519
telemt_connections_bad_total 1443
telemt_handshake_timeouts_total 4341
telemt_upstream_connect_attempt_total 145754
telemt_upstream_connect_success_total 145534
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 145615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 2666
telemt_me_reconnect_attempts_total 109624
telemt_me_reconnect_success_total 109535
telemt_me_reader_eof_total 110828
telemt_me_idle_close_by_peer_total 110823
telemt_me_route_drop_no_conn_total 93992
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 235
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1092
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 16
telemt_pool_force_close_total 405
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 111019
telemt_me_writer_restored_same_endpoint_total 109528
telemt_me_async_recovery_trigger_total 151299
telemt_me_writer_removed_unexpected_minus_restored_total 1491
telemt_user_connections_total{user="hello"} 238713
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 23165803156 (21.57 GB)
telemt_user_octets_to_client{user="hello"} 67380531032 (62.75 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 28758.6 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265194
telemt_connections_bad_total 82373
telemt_handshake_timeouts_total 17107
telemt_upstream_connect_attempt_total 56277
telemt_upstream_connect_success_total 56188
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 56230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1074
telemt_me_reconnect_attempts_total 20002
telemt_me_reconnect_success_total 19970
telemt_me_reader_eof_total 27065
telemt_me_idle_close_by_peer_total 27063
telemt_me_route_drop_no_conn_total 71777
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 256
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 27070
telemt_me_writer_restored_same_endpoint_total 19965
telemt_me_writer_removed_unexpected_minus_restored_total 7105
telemt_user_connections_total{user="hello"} 161508
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1784464100 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 51321209628 (47.80 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 28757.1 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222416
telemt_connections_bad_total 517
telemt_handshake_timeouts_total 2834
telemt_upstream_connect_attempt_total 48767
telemt_upstream_connect_success_total 48582
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 48606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1306
telemt_me_reconnect_attempts_total 14401
telemt_me_reconnect_success_total 14360
telemt_me_reader_eof_total 19801
telemt_me_idle_close_by_peer_total 19799
telemt_me_route_drop_no_conn_total 73414
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 17
telemt_pool_force_close_total 477
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 19870
telemt_me_writer_restored_same_endpoint_total 14352
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5514
telemt_user_connections_total{user="hello"} 204266
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 10272694524 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 71411975636 (66.51 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```
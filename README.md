# Server Metrics 2026-03-04 14:01:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 60629.2 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097996
telemt_connections_bad_total 13918
telemt_handshake_timeouts_total 19192
telemt_upstream_connect_attempt_total 36309
telemt_upstream_connect_success_total 36142
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 36142
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 7843
telemt_me_reconnect_success_total 7785
telemt_me_reader_eof_total 8035
telemt_me_idle_close_by_peer_total 8034
telemt_me_route_drop_no_conn_total 399750
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1883
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1259
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8035
telemt_me_writer_restored_same_endpoint_total 7763
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 870265
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 10088953012 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 294046073736 (273.85 GB)
telemt_user_unique_ips_current{user="hello"} 123
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 60625.6 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422724
telemt_connections_bad_total 3564
telemt_handshake_timeouts_total 29389
telemt_upstream_connect_attempt_total 108710
telemt_upstream_connect_success_total 107076
telemt_upstream_connect_fail_total 778
telemt_upstream_connect_attempts_per_request{bucket="1"} 107070
telemt_upstream_connect_attempts_per_request{bucket="2"} 784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 778
telemt_me_keepalive_timeout_total 1469
telemt_me_reconnect_attempts_total 59622
telemt_me_reconnect_success_total 59528
telemt_me_reader_eof_total 61089
telemt_me_idle_close_by_peer_total 61088
telemt_me_route_drop_no_conn_total 171082
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 254
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 822
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 61169
telemt_me_writer_restored_same_endpoint_total 59503
telemt_me_writer_removed_unexpected_minus_restored_total 1666
telemt_user_connections_total{user="hello"} 327616
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 4203319532 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 103959989588 (96.82 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 60624.4 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830681
telemt_connections_bad_total 180447
telemt_handshake_timeouts_total 29167
telemt_upstream_connect_attempt_total 83301
telemt_upstream_connect_success_total 82780
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 82779
telemt_upstream_connect_attempts_per_request{bucket="2"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 1087
telemt_me_reconnect_attempts_total 37954
telemt_me_reconnect_success_total 37855
telemt_me_reader_eof_total 39849
telemt_me_idle_close_by_peer_total 39845
telemt_me_route_drop_no_conn_total 303273
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1694
telemt_desync_full_logged_total 574
telemt_desync_suppressed_total 1120
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39861
telemt_me_writer_restored_same_endpoint_total 37833
telemt_me_writer_removed_unexpected_minus_restored_total 2028
telemt_user_connections_total{user="hello"} 583417
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 12336759516 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 198137150696 (184.53 GB)
telemt_user_unique_ips_current{user="hello"} 77
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 7301.6 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89976
telemt_connections_bad_total 8894
telemt_handshake_timeouts_total 1599
telemt_upstream_connect_attempt_total 3478
telemt_upstream_connect_success_total 3478
telemt_upstream_connect_attempts_per_request{bucket="1"} 3478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1337
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 511
telemt_me_reader_eof_total 503
telemt_me_idle_close_by_peer_total 503
telemt_me_route_drop_no_conn_total 31761
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 121
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 78103
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 1318101100 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 47976149320 (44.68 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 7661.0 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133928
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 2281
telemt_upstream_connect_attempt_total 4933
telemt_upstream_connect_success_total 4914
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4914
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1206
telemt_me_reconnect_success_total 1216
telemt_me_reader_eof_total 1239
telemt_me_idle_close_by_peer_total 1239
telemt_me_route_drop_no_conn_total 46405
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 363
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1239
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 115170
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 1321510772 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 32224942396 (30.01 GB)
telemt_user_unique_ips_current{user="hello"} 55
```
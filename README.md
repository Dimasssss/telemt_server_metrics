# Server Metrics 2026-03-04 14:31:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 62473.2 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1147618
telemt_connections_bad_total 13927
telemt_handshake_timeouts_total 20900
telemt_upstream_connect_attempt_total 37245
telemt_upstream_connect_success_total 37078
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37078
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 8172
telemt_me_reconnect_success_total 8112
telemt_me_reader_eof_total 8377
telemt_me_idle_close_by_peer_total 8376
telemt_me_route_drop_no_conn_total 424159
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2083
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1393
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 682
telemt_pool_swap_total 16
telemt_pool_force_close_total 682
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8377
telemt_me_writer_restored_same_endpoint_total 8090
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 916119
telemt_user_connections_current{user="hello"} 1078
telemt_user_octets_from_client{user="hello"} 12228501528 (11.39 GB)
telemt_user_octets_to_client{user="hello"} 308234506100 (287.07 GB)
telemt_user_unique_ips_current{user="hello"} 109
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 62469.5 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436245
telemt_connections_bad_total 3745
telemt_handshake_timeouts_total 29597
telemt_upstream_connect_attempt_total 112555
telemt_upstream_connect_success_total 110879
telemt_upstream_connect_fail_total 800
telemt_upstream_connect_attempts_per_request{bucket="1"} 110873
telemt_upstream_connect_attempts_per_request{bucket="2"} 806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 800
telemt_me_keepalive_timeout_total 1501
telemt_me_reconnect_attempts_total 61609
telemt_me_reconnect_success_total 61511
telemt_me_reader_eof_total 63131
telemt_me_idle_close_by_peer_total 63130
telemt_me_route_drop_no_conn_total 177259
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 950
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 63211
telemt_me_writer_restored_same_endpoint_total 61486
telemt_me_writer_removed_unexpected_minus_restored_total 1725
telemt_user_connections_total{user="hello"} 340369
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 4903548488 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 108249260996 (100.81 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 62468.5 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872403
telemt_connections_bad_total 185615
telemt_handshake_timeouts_total 29301
telemt_upstream_connect_attempt_total 84187
telemt_upstream_connect_success_total 83648
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 83647
telemt_upstream_connect_attempts_per_request{bucket="2"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1092
telemt_me_reconnect_attempts_total 38025
telemt_me_reconnect_success_total 37926
telemt_me_reader_eof_total 39924
telemt_me_idle_close_by_peer_total 39920
telemt_me_route_drop_no_conn_total 316985
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1809
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 1209
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39936
telemt_me_writer_restored_same_endpoint_total 37904
telemt_me_writer_removed_unexpected_minus_restored_total 2032
telemt_user_connections_total{user="hello"} 614694
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 12662991496 (11.79 GB)
telemt_user_octets_to_client{user="hello"} 209488956808 (195.10 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 9145.7 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119775
telemt_connections_bad_total 12311
telemt_handshake_timeouts_total 4229
telemt_upstream_connect_attempt_total 4654
telemt_upstream_connect_success_total 4654
telemt_upstream_connect_attempts_per_request{bucket="1"} 4654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1793
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 43745
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 164
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 3
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 101157
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 1574101016 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 55837891636 (52.00 GB)
telemt_user_unique_ips_current{user="hello"} 64
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 9505.0 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163725
telemt_connections_bad_total 1852
telemt_handshake_timeouts_total 2695
telemt_upstream_connect_attempt_total 5590
telemt_upstream_connect_success_total 5561
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5561
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 1227
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1250
telemt_me_route_drop_no_conn_total 58722
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 434
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1250
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 140932
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 1557900252 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 39206542644 (36.51 GB)
telemt_user_unique_ips_current{user="hello"} 74
```
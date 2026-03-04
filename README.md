# Server Metrics 2026-03-04 15:12:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 64933.9 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1210815
telemt_connections_bad_total 14419
telemt_handshake_timeouts_total 22019
telemt_upstream_connect_attempt_total 37867
telemt_upstream_connect_success_total 37700
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37700
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 433
telemt_me_reconnect_attempts_total 8182
telemt_me_reconnect_success_total 8120
telemt_me_reader_eof_total 8385
telemt_me_idle_close_by_peer_total 8384
telemt_me_route_drop_no_conn_total 446364
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2350
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1584
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 881
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8385
telemt_me_writer_restored_same_endpoint_total 8098
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 974498
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 13051091076 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 328264183088 (305.72 GB)
telemt_user_unique_ips_current{user="hello"} 103
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 64930.4 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459597
telemt_connections_bad_total 3826
telemt_handshake_timeouts_total 30274
telemt_upstream_connect_attempt_total 117558
telemt_upstream_connect_success_total 115855
telemt_upstream_connect_fail_total 813
telemt_upstream_connect_attempts_per_request{bucket="1"} 115849
telemt_upstream_connect_attempts_per_request{bucket="2"} 819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 813
telemt_me_keepalive_timeout_total 1547
telemt_me_reconnect_attempts_total 64224
telemt_me_reconnect_success_total 64123
telemt_me_reader_eof_total 65784
telemt_me_idle_close_by_peer_total 65783
telemt_me_route_drop_no_conn_total 187396
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1074
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 748
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 438
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 65864
telemt_me_writer_restored_same_endpoint_total 64098
telemt_me_writer_removed_unexpected_minus_restored_total 1766
telemt_user_connections_total{user="hello"} 362464
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 5724475752 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 115482856300 (107.55 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 64929.2 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927456
telemt_connections_bad_total 192598
telemt_handshake_timeouts_total 29818
telemt_upstream_connect_attempt_total 86073
telemt_upstream_connect_success_total 85503
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 85502
telemt_upstream_connect_attempts_per_request{bucket="2"} 275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1113
telemt_me_reconnect_attempts_total 38567
telemt_me_reconnect_success_total 38466
telemt_me_reader_eof_total 40476
telemt_me_idle_close_by_peer_total 40472
telemt_me_route_drop_no_conn_total 337051
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 266
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1974
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1322
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40488
telemt_me_writer_restored_same_endpoint_total 38444
telemt_me_writer_removed_unexpected_minus_restored_total 2044
telemt_user_connections_total{user="hello"} 660093
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 13658917604 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 224263488948 (208.86 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 11606.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173286
telemt_connections_bad_total 16555
telemt_handshake_timeouts_total 5300
telemt_upstream_connect_attempt_total 5174
telemt_upstream_connect_success_total 5174
telemt_upstream_connect_attempts_per_request{bucket="1"} 5174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2102
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 56483
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 193
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 145582
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1900727568 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 65356749560 (60.87 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 11965.9 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203425
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 6458
telemt_upstream_connect_success_total 6427
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6427
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1318
telemt_me_idle_close_by_peer_total 1318
telemt_me_route_drop_no_conn_total 77078
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 488
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 302
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1318
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 176845
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 2826024832 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 49358104844 (45.97 GB)
telemt_user_unique_ips_current{user="hello"} 68
```
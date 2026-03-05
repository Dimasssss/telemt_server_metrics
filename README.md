# Server Metrics 2026-03-05 00:32:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 13155.7 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106963
telemt_connections_bad_total 1410
telemt_handshake_timeouts_total 768
telemt_upstream_connect_attempt_total 18860
telemt_upstream_connect_success_total 18692
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 18691
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 566
telemt_me_reconnect_attempts_total 9061
telemt_me_reconnect_success_total 9052
telemt_me_reader_eof_total 9389
telemt_me_idle_close_by_peer_total 9388
telemt_me_route_drop_no_conn_total 28972
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 9448
telemt_me_writer_restored_same_endpoint_total 9032
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 93382
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 2902915916 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 50549274292 (47.08 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 13150.6 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41675
telemt_connections_bad_total 786
telemt_handshake_timeouts_total 1047
telemt_upstream_connect_attempt_total 14492
telemt_upstream_connect_success_total 14184
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 14174
telemt_upstream_connect_attempts_per_request{bucket="2"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1026
telemt_me_reconnect_attempts_total 5555
telemt_me_reconnect_success_total 5528
telemt_me_reader_eof_total 5613
telemt_me_idle_close_by_peer_total 5612
telemt_me_route_drop_no_conn_total 12808
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 5717
telemt_me_writer_restored_same_endpoint_total 5503
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 37612
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 333210980 (317.77 MB)
telemt_user_octets_to_client{user="hello"} 10319560824 (9.61 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 13147.3 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96844
telemt_connections_bad_total 1358
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 5951
telemt_upstream_connect_success_total 5895
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 5895
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 304
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 27308
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 303
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 88979
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1058143576 (1009.12 MB)
telemt_user_octets_to_client{user="hello"} 32236086456 (30.02 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 45195.5 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553988
telemt_connections_bad_total 81252
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 21232
telemt_upstream_connect_success_total 21229
telemt_upstream_connect_attempts_per_request{bucket="1"} 21229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 3141
telemt_me_reconnect_success_total 3122
telemt_me_reader_eof_total 3182
telemt_me_idle_close_by_peer_total 3182
telemt_me_route_drop_no_conn_total 186417
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 724
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 18
telemt_pool_force_close_total 507
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 3183
telemt_me_writer_restored_same_endpoint_total 3095
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 429473
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 5854927288 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 159920448648 (148.94 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 45554.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538396
telemt_connections_bad_total 3857
telemt_handshake_timeouts_total 5913
telemt_upstream_connect_attempt_total 29308
telemt_upstream_connect_success_total 29151
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 29151
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 6542
telemt_me_reconnect_success_total 6520
telemt_me_reader_eof_total 6765
telemt_me_idle_close_by_peer_total 6764
telemt_me_route_drop_no_conn_total 236888
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 842
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6770
telemt_me_writer_restored_same_endpoint_total 6498
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 487834
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 7385336336 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 163185830180 (151.98 GB)
telemt_user_unique_ips_current{user="hello"} 27
```
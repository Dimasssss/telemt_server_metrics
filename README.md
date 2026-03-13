# Server Metrics 2026-03-13 20:52:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 140012.5 (38h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4437125
telemt_connections_bad_total 37961
telemt_handshake_timeouts_total 106266
telemt_upstream_connect_attempt_total 29243
telemt_upstream_connect_success_total 29044
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 29243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 6558
telemt_me_reconnect_attempts_total 29842
telemt_me_reconnect_success_total 19724
telemt_me_reader_eof_total 21168
telemt_me_idle_close_by_peer_total 21167
telemt_me_route_drop_no_conn_total 1671565
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4063085
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16168
telemt_desync_full_logged_total 4309
telemt_desync_suppressed_total 11859
telemt_desync_frames_bucket_total{bucket="1_2"} 4036
telemt_desync_frames_bucket_total{bucket="3_10"} 6165
telemt_desync_frames_bucket_total{bucket="gt_10"} 5967
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20322
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19711
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 4065220
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 59932923412 (55.82 GB)
telemt_user_octets_to_client{user="hello"} 1284668553193 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39676.3 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555709
telemt_connections_bad_total 41413
telemt_handshake_timeouts_total 12186
telemt_upstream_connect_attempt_total 11407
telemt_upstream_connect_success_total 11186
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 11407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 1887
telemt_me_reconnect_attempts_total 10578
telemt_me_reconnect_success_total 7156
telemt_me_reader_eof_total 7556
telemt_me_idle_close_by_peer_total 7555
telemt_me_route_drop_no_conn_total 205096
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482277
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1633
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7365
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7148
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 484206
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 5206018757 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 153930009148 (143.36 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 169633.0 (47h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3228523
telemt_connections_bad_total 30070
telemt_handshake_timeouts_total 215135
telemt_upstream_connect_attempt_total 37748
telemt_upstream_connect_success_total 37728
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 37748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 10230
telemt_me_reconnect_attempts_total 33898
telemt_me_reconnect_success_total 28955
telemt_me_reader_eof_total 30720
telemt_me_idle_close_by_peer_total 30719
telemt_me_route_drop_no_conn_total 1106475
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2677430
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8845
telemt_desync_full_logged_total 2966
telemt_desync_suppressed_total 5879
telemt_desync_frames_bucket_total{bucket="1_2"} 1463
telemt_desync_frames_bucket_total{bucket="3_10"} 3227
telemt_desync_frames_bucket_total{bucket="gt_10"} 4155
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 29379
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 28914
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 2676709
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 44046642636 (41.02 GB)
telemt_user_octets_to_client{user="hello"} 943450493909 (878.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 169633.5 (47h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2095663
telemt_connections_bad_total 22788
telemt_handshake_timeouts_total 200142
telemt_upstream_connect_attempt_total 52808
telemt_upstream_connect_success_total 50368
telemt_upstream_connect_fail_total 2303
telemt_upstream_connect_attempts_per_request{bucket="1"} 52534
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2302
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20219
telemt_me_reconnect_attempts_total 43905
telemt_me_reconnect_success_total 34894
telemt_me_reader_eof_total 37461
telemt_me_idle_close_by_peer_total 37454
telemt_me_route_drop_no_conn_total 740177
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1725860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3696
telemt_desync_full_logged_total 1184
telemt_desync_suppressed_total 2512
telemt_desync_frames_bucket_total{bucket="1_2"} 980
telemt_desync_frames_bucket_total{bucket="3_10"} 1533
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 35475
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34870
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 1731731
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 26901977055 (25.05 GB)
telemt_user_octets_to_client{user="hello"} 647681087930 (603.20 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39069.1 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593366
telemt_connections_bad_total 5791
telemt_handshake_timeouts_total 5577
telemt_upstream_connect_attempt_total 8616
telemt_upstream_connect_success_total 8333
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 8616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 971
telemt_me_reconnect_attempts_total 30976
telemt_me_reconnect_success_total 6356
telemt_me_reader_eof_total 7246
telemt_me_idle_close_by_peer_total 7245
telemt_me_route_drop_no_conn_total 224978
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557127
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7182
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6352
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 826
telemt_user_connections_total{user="hello"} 557056
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 8320862916 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 176799710000 (164.66 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 64
```
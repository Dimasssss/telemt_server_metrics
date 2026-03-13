# Server Metrics 2026-03-13 12:32:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110023.7 (30h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3277278
telemt_connections_bad_total 36584
telemt_handshake_timeouts_total 57041
telemt_upstream_connect_attempt_total 21753
telemt_upstream_connect_success_total 21633
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 2095
telemt_me_reconnect_attempts_total 26220
telemt_me_reconnect_success_total 16139
telemt_me_reader_eof_total 17351
telemt_me_idle_close_by_peer_total 17350
telemt_me_route_drop_no_conn_total 1215222
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3003608
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12709
telemt_desync_full_logged_total 3295
telemt_desync_suppressed_total 9414
telemt_desync_frames_bucket_total{bucket="1_2"} 3243
telemt_desync_frames_bucket_total{bucket="3_10"} 4793
telemt_desync_frames_bucket_total{bucket="gt_10"} 4673
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16676
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16126
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 3003523
telemt_user_connections_current{user="hello"} 1872
telemt_user_octets_from_client{user="hello"} 41627769208 (38.77 GB)
telemt_user_octets_to_client{user="hello"} 969077305148 (902.52 GB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9687.5 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132013
telemt_connections_bad_total 7536
telemt_handshake_timeouts_total 3058
telemt_upstream_connect_attempt_total 2408
telemt_upstream_connect_success_total 2335
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 2408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3032
telemt_me_reconnect_success_total 1806
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1890
telemt_me_route_drop_no_conn_total 46574
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1855
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1799
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 118133
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 1152294320 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 31018556012 (28.89 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 139644.2 (38h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2487602
telemt_connections_bad_total 26316
telemt_handshake_timeouts_total 164392
telemt_upstream_connect_attempt_total 31824
telemt_upstream_connect_success_total 31814
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3161
telemt_me_reconnect_attempts_total 27042
telemt_me_reconnect_success_total 24497
telemt_me_reader_eof_total 25972
telemt_me_idle_close_by_peer_total 25971
telemt_me_route_drop_no_conn_total 830344
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2018926
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6755
telemt_desync_full_logged_total 2176
telemt_desync_suppressed_total 4579
telemt_desync_frames_bucket_total{bucket="1_2"} 1065
telemt_desync_frames_bucket_total{bucket="3_10"} 2470
telemt_desync_frames_bucket_total{bucket="gt_10"} 3220
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 24779
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24456
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 2018338
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 34203822836 (31.85 GB)
telemt_user_octets_to_client{user="hello"} 724301652933 (674.56 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 139644.8 (38h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1585875
telemt_connections_bad_total 17869
telemt_handshake_timeouts_total 111253
telemt_upstream_connect_attempt_total 45133
telemt_upstream_connect_success_total 42813
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 44859
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11824
telemt_me_reconnect_attempts_total 38948
telemt_me_reconnect_success_total 29984
telemt_me_reader_eof_total 32243
telemt_me_idle_close_by_peer_total 32236
telemt_me_route_drop_no_conn_total 562996
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1321808
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2554
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 1713
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 1009
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 30484
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29960
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 1326531
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 19730140553 (18.38 GB)
telemt_user_octets_to_client{user="hello"} 517173763630 (481.66 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9080.3 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132192
telemt_connections_bad_total 815
telemt_handshake_timeouts_total 1098
telemt_upstream_connect_attempt_total 1787
telemt_upstream_connect_success_total 1716
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 1786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 9287
telemt_me_reconnect_success_total 1217
telemt_me_reader_eof_total 1446
telemt_me_idle_close_by_peer_total 1446
telemt_me_route_drop_no_conn_total 52130
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125924
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 483
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1462
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1213
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 125919
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 1408508412 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 41162959720 (38.34 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 123
```
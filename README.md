# Server Metrics 2026-03-11 16:43:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94605.7 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2363567
telemt_connections_bad_total 41015
telemt_handshake_timeouts_total 54042
telemt_upstream_connect_attempt_total 19739
telemt_upstream_connect_success_total 19727
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5072
telemt_me_reconnect_attempts_total 32807
telemt_me_reconnect_success_total 14932
telemt_me_reader_eof_total 16195
telemt_me_idle_close_by_peer_total 16195
telemt_me_route_drop_no_conn_total 876900
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2162706
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11220
telemt_desync_full_logged_total 3063
telemt_desync_suppressed_total 8157
telemt_desync_frames_bucket_total{bucket="1_2"} 2772
telemt_desync_frames_bucket_total{bucket="3_10"} 4329
telemt_desync_frames_bucket_total{bucket="gt_10"} 4119
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15656
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14926
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 2161156
telemt_user_connections_current{user="hello"} 1429
telemt_user_octets_from_client{user="hello"} 29095223264 (27.10 GB)
telemt_user_octets_to_client{user="hello"} 609514418820 (567.65 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94662.5 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886498
telemt_connections_bad_total 15496
telemt_handshake_timeouts_total 72637
telemt_upstream_connect_attempt_total 29821
telemt_upstream_connect_success_total 26861
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 29821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2653
telemt_me_reconnect_attempts_total 21234
telemt_me_reconnect_success_total 19133
telemt_me_reader_eof_total 20244
telemt_me_idle_close_by_peer_total 20241
telemt_me_route_drop_no_conn_total 339689
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742942
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2978
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2027
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1072
telemt_desync_frames_bucket_total{bucket="gt_10"} 997
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19407
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19110
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 745401
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 8512245666 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 210363736816 (195.92 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94662.4 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1515067
telemt_connections_bad_total 8938
telemt_handshake_timeouts_total 125932
telemt_upstream_connect_attempt_total 24419
telemt_upstream_connect_success_total 24107
telemt_upstream_connect_fail_total 312
telemt_upstream_connect_attempts_per_request{bucket="1"} 24419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 312
telemt_me_keepalive_timeout_total 1753
telemt_me_reconnect_attempts_total 41993
telemt_me_reconnect_success_total 18239
telemt_me_reader_eof_total 19795
telemt_me_idle_close_by_peer_total 19795
telemt_me_route_drop_no_conn_total 553862
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1324824
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3464
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 2438
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 1305
telemt_desync_frames_bucket_total{bucket="gt_10"} 1295
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19230
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18227
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 991
telemt_user_connections_total{user="hello"} 1324530
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 16112958601 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 401334280649 (373.77 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94663.0 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091704
telemt_connections_bad_total 77986
telemt_handshake_timeouts_total 105055
telemt_upstream_connect_attempt_total 25526
telemt_upstream_connect_success_total 25526
telemt_upstream_connect_attempts_per_request{bucket="1"} 25526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1149
telemt_me_reconnect_attempts_total 22436
telemt_me_reconnect_success_total 20782
telemt_me_reader_eof_total 22025
telemt_me_idle_close_by_peer_total 22024
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 358400
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875618
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1820
telemt_desync_full_logged_total 702
telemt_desync_suppressed_total 1118
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21054
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 20751
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 874923
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 10512154420 (9.79 GB)
telemt_user_octets_to_client{user="hello"} 258171219268 (240.44 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94662.4 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1204280
telemt_connections_bad_total 6957
telemt_handshake_timeouts_total 11897
telemt_upstream_connect_attempt_total 25852
telemt_upstream_connect_success_total 25737
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 25852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2150
telemt_me_reconnect_attempts_total 24943
telemt_me_reconnect_success_total 20846
telemt_me_reader_eof_total 21960
telemt_me_idle_close_by_peer_total 21960
telemt_me_route_drop_no_conn_total 429607
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097384
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4296
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 2761
telemt_desync_frames_bucket_total{bucket="1_2"} 1414
telemt_desync_frames_bucket_total{bucket="3_10"} 1603
telemt_desync_frames_bucket_total{bucket="gt_10"} 1279
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 21246
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20846
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 1097082
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 20511576999 (19.10 GB)
telemt_user_octets_to_client{user="hello"} 380556722018 (354.42 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 89
```
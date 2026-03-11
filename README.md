# Server Metrics 2026-03-11 21:29:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 111753.1 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2817993
telemt_connections_bad_total 65638
telemt_handshake_timeouts_total 62619
telemt_upstream_connect_attempt_total 23860
telemt_upstream_connect_success_total 23848
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5443
telemt_me_reconnect_attempts_total 36069
telemt_me_reconnect_success_total 18170
telemt_me_reader_eof_total 19608
telemt_me_idle_close_by_peer_total 19608
telemt_me_route_drop_no_conn_total 1056516
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2554035
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12740
telemt_desync_full_logged_total 3541
telemt_desync_suppressed_total 9199
telemt_desync_frames_bucket_total{bucket="1_2"} 3146
telemt_desync_frames_bucket_total{bucket="3_10"} 4889
telemt_desync_frames_bucket_total{bucket="gt_10"} 4705
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 18940
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18164
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 770
telemt_user_connections_total{user="hello"} 2552368
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 38827462016 (36.16 GB)
telemt_user_octets_to_client{user="hello"} 737607921672 (686.95 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 111809.9 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026611
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90482
telemt_upstream_connect_attempt_total 33987
telemt_upstream_connect_success_total 31008
telemt_upstream_connect_fail_total 2979
telemt_upstream_connect_attempts_per_request{bucket="1"} 33987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2979
telemt_me_keepalive_timeout_total 2915
telemt_me_reconnect_attempts_total 24551
telemt_me_reconnect_success_total 22421
telemt_me_reader_eof_total 23765
telemt_me_idle_close_by_peer_total 23762
telemt_me_route_drop_no_conn_total 388040
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 859213
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3385
telemt_desync_full_logged_total 1103
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 22751
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22398
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 861649
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 10422175194 (9.71 GB)
telemt_user_octets_to_client{user="hello"} 260872861156 (242.96 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 111809.7 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795461
telemt_connections_bad_total 11437
telemt_handshake_timeouts_total 137500
telemt_upstream_connect_attempt_total 45645
telemt_upstream_connect_success_total 45284
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 45644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 2060
telemt_me_reconnect_attempts_total 63929
telemt_me_reconnect_success_total 20701
telemt_me_reader_eof_total 22911
telemt_me_idle_close_by_peer_total 22911
telemt_me_route_drop_no_conn_total 646714
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1562085
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4215
telemt_desync_full_logged_total 1244
telemt_desync_suppressed_total 2971
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1604
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22334
telemt_me_refill_failed_total 1345
telemt_me_writer_restored_same_endpoint_total 20689
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1633
telemt_user_connections_total{user="hello"} 1579540
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 20062623250 (18.68 GB)
telemt_user_octets_to_client{user="hello"} 482291096586 (449.17 GB)
telemt_user_msgs_from_client{user="hello"} 215822
telemt_user_msgs_to_client{user="hello"} 1364628
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 111810.1 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284504
telemt_connections_bad_total 78289
telemt_handshake_timeouts_total 111920
telemt_upstream_connect_attempt_total 29973
telemt_upstream_connect_success_total 29973
telemt_upstream_connect_attempts_per_request{bucket="1"} 29973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1555
telemt_me_reconnect_attempts_total 28985
telemt_me_reconnect_success_total 24364
telemt_me_reader_eof_total 25883
telemt_me_idle_close_by_peer_total 25882
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 430720
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1058238
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24770
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24331
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 1057358
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 12358017788 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 318948824660 (297.04 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16486.2 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220589
telemt_connections_bad_total 5183
telemt_handshake_timeouts_total 2488
telemt_upstream_connect_attempt_total 4757
telemt_upstream_connect_success_total 4756
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3890
telemt_me_reconnect_success_total 3853
telemt_me_reader_eof_total 3994
telemt_me_idle_close_by_peer_total 3994
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 74596
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195618
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 490
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3898
telemt_me_writer_restored_same_endpoint_total 3826
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 195580
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 9730668108 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 67373402644 (62.75 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 39
```
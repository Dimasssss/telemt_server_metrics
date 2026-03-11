# Server Metrics 2026-03-11 10:20:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71628.6 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568629
telemt_connections_bad_total 24742
telemt_handshake_timeouts_total 41310
telemt_upstream_connect_attempt_total 14823
telemt_upstream_connect_success_total 14814
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 798
telemt_me_reconnect_attempts_total 22889
telemt_me_reconnect_success_total 11199
telemt_me_reader_eof_total 12117
telemt_me_idle_close_by_peer_total 12117
telemt_me_route_drop_no_conn_total 578277
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1422982
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7094
telemt_desync_full_logged_total 1956
telemt_desync_suppressed_total 5138
telemt_desync_frames_bucket_total{bucket="1_2"} 1872
telemt_desync_frames_bucket_total{bucket="3_10"} 2675
telemt_desync_frames_bucket_total{bucket="gt_10"} 2547
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11674
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11193
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 1421562
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 18512056424 (17.24 GB)
telemt_user_octets_to_client{user="hello"} 406235775552 (378.34 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71685.3 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600136
telemt_connections_bad_total 10181
telemt_handshake_timeouts_total 36166
telemt_upstream_connect_attempt_total 23886
telemt_upstream_connect_success_total 20956
telemt_upstream_connect_fail_total 2930
telemt_upstream_connect_attempts_per_request{bucket="1"} 23886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2930
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 15265
telemt_me_reconnect_success_total 14422
telemt_me_reader_eof_total 15275
telemt_me_idle_close_by_peer_total 15273
telemt_me_route_drop_no_conn_total 246890
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508143
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2282
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1574
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 704
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14600
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14400
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 510370
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 4979779646 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 142375178568 (132.60 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71685.2 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040051
telemt_connections_bad_total 7700
telemt_handshake_timeouts_total 100672
telemt_upstream_connect_attempt_total 19388
telemt_upstream_connect_success_total 19148
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 19388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 806
telemt_me_reconnect_attempts_total 28098
telemt_me_reconnect_success_total 14481
telemt_me_reader_eof_total 15560
telemt_me_idle_close_by_peer_total 15560
telemt_me_route_drop_no_conn_total 343969
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891865
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2537
telemt_desync_full_logged_total 749
telemt_desync_suppressed_total 1788
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 15092
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14470
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 892676
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 10545347353 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 273694896945 (254.90 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71685.8 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758269
telemt_connections_bad_total 67461
telemt_handshake_timeouts_total 72691
telemt_upstream_connect_attempt_total 19665
telemt_upstream_connect_success_total 19665
telemt_upstream_connect_attempts_per_request{bucket="1"} 19665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 747
telemt_me_reconnect_attempts_total 17145
telemt_me_reconnect_success_total 16088
telemt_me_reader_eof_total 17082
telemt_me_idle_close_by_peer_total 17081
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 238298
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595653
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1287
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 477
telemt_desync_frames_bucket_total{bucket="gt_10"} 364
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16277
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16064
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 595025
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 6853839708 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 171844282572 (160.04 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71685.3 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806989
telemt_connections_bad_total 6085
telemt_handshake_timeouts_total 7747
telemt_upstream_connect_attempt_total 19268
telemt_upstream_connect_success_total 19188
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 19268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 809
telemt_me_reconnect_attempts_total 19290
telemt_me_reconnect_success_total 15495
telemt_me_reader_eof_total 16386
telemt_me_idle_close_by_peer_total 16386
telemt_me_route_drop_no_conn_total 279184
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733188
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3063
telemt_desync_full_logged_total 1147
telemt_desync_suppressed_total 1916
telemt_desync_frames_bucket_total{bucket="1_2"} 1064
telemt_desync_frames_bucket_total{bucket="3_10"} 1241
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 15808
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15495
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 732893
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 11284859087 (10.51 GB)
telemt_user_octets_to_client{user="hello"} 268400939870 (249.97 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 112
```
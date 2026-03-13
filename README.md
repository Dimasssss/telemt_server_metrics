# Server Metrics 2026-03-13 05:12:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83636.9 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2253232
telemt_connections_bad_total 32698
telemt_handshake_timeouts_total 23629
telemt_upstream_connect_attempt_total 16455
telemt_upstream_connect_success_total 16363
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1308
telemt_me_reconnect_attempts_total 21081
telemt_me_reconnect_success_total 12214
telemt_me_reader_eof_total 13180
telemt_me_idle_close_by_peer_total 13179
telemt_me_route_drop_no_conn_total 858821
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2072080
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9186
telemt_desync_full_logged_total 2367
telemt_desync_suppressed_total 6819
telemt_desync_frames_bucket_total{bucket="1_2"} 2399
telemt_desync_frames_bucket_total{bucket="3_10"} 3341
telemt_desync_frames_bucket_total{bucket="gt_10"} 3446
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12661
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12201
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 2071502
telemt_user_connections_current{user="hello"} 1050
telemt_user_octets_from_client{user="hello"} 30068357180 (28.00 GB)
telemt_user_octets_to_client{user="hello"} 713644522740 (664.63 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 113257.5 (31h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915042
telemt_connections_bad_total 12372
telemt_handshake_timeouts_total 39980
telemt_upstream_connect_attempt_total 28669
telemt_upstream_connect_success_total 28638
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3536
telemt_me_reconnect_attempts_total 21489
telemt_me_reconnect_success_total 21372
telemt_me_reader_eof_total 22782
telemt_me_idle_close_by_peer_total 22782
telemt_me_route_drop_no_conn_total 291415
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824737
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3259
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 2231
telemt_desync_frames_bucket_total{bucket="1_2"} 1299
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21582
telemt_me_writer_restored_same_endpoint_total 21363
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 826632
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 13255529580 (12.35 GB)
telemt_user_octets_to_client{user="hello"} 316324140431 (294.60 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 113257.4 (31h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1889171
telemt_connections_bad_total 18932
telemt_handshake_timeouts_total 124120
telemt_upstream_connect_attempt_total 26354
telemt_upstream_connect_success_total 26344
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1643
telemt_me_reconnect_attempts_total 21639
telemt_me_reconnect_success_total 20371
telemt_me_reader_eof_total 21575
telemt_me_idle_close_by_peer_total 21574
telemt_me_route_drop_no_conn_total 608012
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489774
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5164
telemt_desync_full_logged_total 1581
telemt_desync_suppressed_total 3583
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 1863
telemt_desync_frames_bucket_total{bucket="gt_10"} 2466
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 20565
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20330
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 1489273
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 25611199516 (23.85 GB)
telemt_user_octets_to_client{user="hello"} 529062595037 (492.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 113257.8 (31h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1162128
telemt_connections_bad_total 13218
telemt_handshake_timeouts_total 75404
telemt_upstream_connect_attempt_total 38779
telemt_upstream_connect_success_total 36494
telemt_upstream_connect_fail_total 2148
telemt_upstream_connect_attempts_per_request{bucket="1"} 38505
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2147
telemt_me_keepalive_timeout_total 11397
telemt_me_reconnect_attempts_total 33938
telemt_me_reconnect_success_total 25004
telemt_me_reader_eof_total 26983
telemt_me_idle_close_by_peer_total 26976
telemt_me_route_drop_no_conn_total 413948
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1975
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 25454
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24980
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 1006040
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 15350756721 (14.30 GB)
telemt_user_octets_to_client{user="hello"} 396874309254 (369.62 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 113257.4 (31h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1298341
telemt_connections_bad_total 12924
telemt_handshake_timeouts_total 10387
telemt_upstream_connect_attempt_total 35797
telemt_upstream_connect_success_total 35367
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 35797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 1958
telemt_me_reconnect_attempts_total 43477
telemt_me_reconnect_success_total 29744
telemt_me_reader_eof_total 31244
telemt_me_idle_close_by_peer_total 31244
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 480351
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1202051
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4353
telemt_desync_full_logged_total 1568
telemt_desync_suppressed_total 2785
telemt_desync_frames_bucket_total{bucket="1_2"} 1315
telemt_desync_frames_bucket_total{bucket="3_10"} 1418
telemt_desync_frames_bucket_total{bucket="gt_10"} 1620
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 30507
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29693
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1201908
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 14588645732 (13.59 GB)
telemt_user_octets_to_client{user="hello"} 408225292980 (380.19 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 84
```
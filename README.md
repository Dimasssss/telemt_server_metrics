# Server Metrics 2026-03-11 10:36:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72547.3 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1597171
telemt_connections_bad_total 24743
telemt_handshake_timeouts_total 41728
telemt_upstream_connect_attempt_total 15011
telemt_upstream_connect_success_total 15002
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 801
telemt_me_reconnect_attempts_total 23034
telemt_me_reconnect_success_total 11342
telemt_me_reader_eof_total 12273
telemt_me_idle_close_by_peer_total 12273
telemt_me_route_drop_no_conn_total 588744
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1450291
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7291
telemt_desync_full_logged_total 2002
telemt_desync_suppressed_total 5289
telemt_desync_frames_bucket_total{bucket="1_2"} 1910
telemt_desync_frames_bucket_total{bucket="3_10"} 2755
telemt_desync_frames_bucket_total{bucket="gt_10"} 2626
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11818
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11336
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 1448873
telemt_user_connections_current{user="hello"} 1293
telemt_user_octets_from_client{user="hello"} 18844675560 (17.55 GB)
telemt_user_octets_to_client{user="hello"} 413449591220 (385.05 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72604.1 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611899
telemt_connections_bad_total 10183
telemt_handshake_timeouts_total 38126
telemt_upstream_connect_attempt_total 24083
telemt_upstream_connect_success_total 21151
telemt_upstream_connect_fail_total 2932
telemt_upstream_connect_attempts_per_request{bucket="1"} 24083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2932
telemt_me_keepalive_timeout_total 2156
telemt_me_reconnect_attempts_total 15417
telemt_me_reconnect_success_total 14572
telemt_me_reader_eof_total 15438
telemt_me_idle_close_by_peer_total 15436
telemt_me_route_drop_no_conn_total 250482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517627
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2333
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1609
telemt_desync_frames_bucket_total{bucket="1_2"} 772
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 726
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14752
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14550
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 519853
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 5121941978 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 145108870968 (135.14 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 72604.0 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1058896
telemt_connections_bad_total 7701
telemt_handshake_timeouts_total 102266
telemt_upstream_connect_attempt_total 19608
telemt_upstream_connect_success_total 19364
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 809
telemt_me_reconnect_attempts_total 28271
telemt_me_reconnect_success_total 14652
telemt_me_reader_eof_total 15747
telemt_me_idle_close_by_peer_total 15747
telemt_me_route_drop_no_conn_total 350997
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908553
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2560
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1803
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 952
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 15265
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14641
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 909372
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 10671983273 (9.94 GB)
telemt_user_octets_to_client{user="hello"} 277068215337 (258.04 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 72604.4 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771338
telemt_connections_bad_total 68296
telemt_handshake_timeouts_total 73453
telemt_upstream_connect_attempt_total 19856
telemt_upstream_connect_success_total 19856
telemt_upstream_connect_attempts_per_request{bucket="1"} 19856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 17293
telemt_me_reconnect_success_total 16235
telemt_me_reader_eof_total 17241
telemt_me_idle_close_by_peer_total 17240
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 243323
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606943
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1336
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16428
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16211
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 606314
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 6958763132 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 174174733968 (162.21 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72604.3 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823372
telemt_connections_bad_total 6086
telemt_handshake_timeouts_total 7788
telemt_upstream_connect_attempt_total 19486
telemt_upstream_connect_success_total 19404
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 19486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 816
telemt_me_reconnect_attempts_total 19462
telemt_me_reconnect_success_total 15665
telemt_me_reader_eof_total 16558
telemt_me_idle_close_by_peer_total 16558
telemt_me_route_drop_no_conn_total 285633
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747050
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3097
telemt_desync_full_logged_total 1158
telemt_desync_suppressed_total 1939
telemt_desync_frames_bucket_total{bucket="1_2"} 1070
telemt_desync_frames_bucket_total{bucket="3_10"} 1251
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 15980
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15665
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 746778
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 11390955647 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 273594500682 (254.80 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 116
```
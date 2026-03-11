# Server Metrics 2026-03-11 06:11:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56660.2 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114659
telemt_connections_bad_total 13233
telemt_handshake_timeouts_total 38181
telemt_upstream_connect_attempt_total 11976
telemt_upstream_connect_success_total 11967
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 689
telemt_me_reconnect_attempts_total 20785
telemt_me_reconnect_success_total 9103
telemt_me_reader_eof_total 9902
telemt_me_idle_close_by_peer_total 9902
telemt_me_route_drop_no_conn_total 410224
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000514
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4660
telemt_desync_full_logged_total 1310
telemt_desync_suppressed_total 3350
telemt_desync_frames_bucket_total{bucket="1_2"} 1287
telemt_desync_frames_bucket_total{bucket="3_10"} 1749
telemt_desync_frames_bucket_total{bucket="gt_10"} 1624
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9553
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9097
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 1000187
telemt_user_connections_current{user="hello"} 1195
telemt_user_octets_from_client{user="hello"} 13396885364 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 293909603512 (273.72 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56717.0 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428671
telemt_connections_bad_total 4200
telemt_handshake_timeouts_total 20793
telemt_upstream_connect_attempt_total 20627
telemt_upstream_connect_success_total 17720
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 2010
telemt_me_reconnect_attempts_total 12766
telemt_me_reconnect_success_total 11943
telemt_me_reader_eof_total 12619
telemt_me_idle_close_by_peer_total 12617
telemt_me_route_drop_no_conn_total 197003
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367532
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1909
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12081
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11921
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 369802
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 3727554522 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 90680715908 (84.45 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56716.9 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732426
telemt_connections_bad_total 6249
telemt_handshake_timeouts_total 40409
telemt_upstream_connect_attempt_total 15284
telemt_upstream_connect_success_total 15083
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 22256
telemt_me_reconnect_success_total 11183
telemt_me_reader_eof_total 12064
telemt_me_idle_close_by_peer_total 12064
telemt_me_route_drop_no_conn_total 246979
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1856
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1321
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 11675
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11172
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 655128
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 7819118033 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 193649324105 (180.35 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56717.3 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556707
telemt_connections_bad_total 53225
telemt_handshake_timeouts_total 57736
telemt_upstream_connect_attempt_total 16177
telemt_upstream_connect_success_total 16177
telemt_upstream_connect_attempts_per_request{bucket="1"} 16177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 642
telemt_me_reconnect_attempts_total 14396
telemt_me_reconnect_success_total 13351
telemt_me_reader_eof_total 14174
telemt_me_idle_close_by_peer_total 14174
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 165468
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430812
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 915
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13506
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13329
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 430387
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 5217760600 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 118590898380 (110.45 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56716.9 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582510
telemt_connections_bad_total 5959
telemt_handshake_timeouts_total 3972
telemt_upstream_connect_attempt_total 16172
telemt_upstream_connect_success_total 16105
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 16172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 670
telemt_me_reconnect_attempts_total 16946
telemt_me_reconnect_success_total 13163
telemt_me_reader_eof_total 13900
telemt_me_idle_close_by_peer_total 13900
telemt_me_route_drop_no_conn_total 190484
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530981
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2548
telemt_desync_full_logged_total 986
telemt_desync_suppressed_total 1562
telemt_desync_frames_bucket_total{bucket="1_2"} 916
telemt_desync_frames_bucket_total{bucket="3_10"} 1088
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 13449
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13163
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 530718
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 9376755295 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 185005580406 (172.30 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 82
```
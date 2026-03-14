# Server Metrics 2026-03-14 02:34:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 160556.8 (44h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4673421
telemt_connections_bad_total 39820
telemt_handshake_timeouts_total 108457
telemt_upstream_connect_attempt_total 33956
telemt_upstream_connect_success_total 33730
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 33956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 6725
telemt_me_reconnect_attempts_total 33528
telemt_me_reconnect_success_total 23387
telemt_me_reader_eof_total 25083
telemt_me_idle_close_by_peer_total 25082
telemt_me_route_drop_no_conn_total 1770281
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4285417
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16756
telemt_desync_full_logged_total 4519
telemt_desync_suppressed_total 12237
telemt_desync_frames_bucket_total{bucket="1_2"} 4186
telemt_desync_frames_bucket_total{bucket="3_10"} 6394
telemt_desync_frames_bucket_total{bucket="gt_10"} 6176
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 24039
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23374
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 4287220
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 62919202748 (58.60 GB)
telemt_user_octets_to_client{user="hello"} 1354865385613 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60220.4 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697494
telemt_connections_bad_total 50964
telemt_handshake_timeouts_total 13109
telemt_upstream_connect_attempt_total 16821
telemt_upstream_connect_success_total 16569
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 16821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 2060
telemt_me_reconnect_attempts_total 14990
telemt_me_reconnect_success_total 11545
telemt_me_reader_eof_total 12252
telemt_me_idle_close_by_peer_total 12251
telemt_me_route_drop_no_conn_total 234541
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558412
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1683
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11811
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11537
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 560363
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 5982274809 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 180122672976 (167.75 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 190177.1 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3377736
telemt_connections_bad_total 34970
telemt_handshake_timeouts_total 223324
telemt_upstream_connect_attempt_total 42841
telemt_upstream_connect_success_total 42820
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10421
telemt_me_reconnect_attempts_total 37993
telemt_me_reconnect_success_total 33031
telemt_me_reader_eof_total 35083
telemt_me_idle_close_by_peer_total 35082
telemt_me_route_drop_no_conn_total 1157920
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2811053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9338
telemt_desync_full_logged_total 3119
telemt_desync_suppressed_total 6219
telemt_desync_frames_bucket_total{bucket="1_2"} 1609
telemt_desync_frames_bucket_total{bucket="3_10"} 3377
telemt_desync_frames_bucket_total{bucket="gt_10"} 4352
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 33495
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32990
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2810278
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 45182740012 (42.08 GB)
telemt_user_octets_to_client{user="hello"} 1005035456453 (936.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 190179.6 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2256129
telemt_connections_bad_total 22970
telemt_handshake_timeouts_total 246536
telemt_upstream_connect_attempt_total 59618
telemt_upstream_connect_success_total 57155
telemt_upstream_connect_fail_total 2326
telemt_upstream_connect_attempts_per_request{bucket="1"} 59344
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2325
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20422
telemt_me_reconnect_attempts_total 49689
telemt_me_reconnect_success_total 40657
telemt_me_reader_eof_total 43607
telemt_me_idle_close_by_peer_total 43600
telemt_me_route_drop_no_conn_total 771615
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1800374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 41289
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40633
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 1806301
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 27601464867 (25.71 GB)
telemt_user_octets_to_client{user="hello"} 666578185082 (620.80 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59613.1 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697937
telemt_connections_bad_total 7911
telemt_handshake_timeouts_total 8663
telemt_upstream_connect_attempt_total 15154
telemt_upstream_connect_success_total 14737
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 15154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 43900
telemt_me_reconnect_success_total 11737
telemt_me_reader_eof_total 13047
telemt_me_idle_close_by_peer_total 13046
telemt_me_route_drop_no_conn_total 264938
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650023
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1693
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 529
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12845
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11732
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1108
telemt_user_connections_total{user="hello"} 649907
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 11901428884 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 211790439316 (197.25 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 30
```
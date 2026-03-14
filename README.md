# Server Metrics 2026-03-14 10:35:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 189415.1 (52h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5437959
telemt_connections_bad_total 56089
telemt_handshake_timeouts_total 120234
telemt_upstream_connect_attempt_total 39823
telemt_upstream_connect_success_total 39567
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7616
telemt_me_reconnect_attempts_total 41519
telemt_me_reconnect_success_total 27805
telemt_me_reader_eof_total 29874
telemt_me_idle_close_by_peer_total 29873
telemt_me_route_drop_no_conn_total 2055668
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4983753
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19011
telemt_desync_full_logged_total 5212
telemt_desync_suppressed_total 13799
telemt_desync_frames_bucket_total{bucket="1_2"} 4660
telemt_desync_frames_bucket_total{bucket="3_10"} 7244
telemt_desync_frames_bucket_total{bucket="gt_10"} 7107
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28639
telemt_me_refill_failed_total 423
telemt_me_writer_restored_same_endpoint_total 27792
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 834
telemt_user_connections_total{user="hello"} 4985204
telemt_user_connections_current{user="hello"} 1667
telemt_user_octets_from_client{user="hello"} 76490526312 (71.24 GB)
telemt_user_octets_to_client{user="hello"} 1586626708781 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89078.8 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006908
telemt_connections_bad_total 57873
telemt_handshake_timeouts_total 22177
telemt_upstream_connect_attempt_total 23351
telemt_upstream_connect_success_total 23059
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 23351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 44
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 2264
telemt_me_reconnect_attempts_total 26487
telemt_me_reconnect_success_total 16611
telemt_me_reader_eof_total 17801
telemt_me_idle_close_by_peer_total 17800
telemt_me_route_drop_no_conn_total 338561
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822374
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2301
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1579
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17155
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16603
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 824275
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 8954576873 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 289168091032 (269.31 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 219035.6 (60h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3864371
telemt_connections_bad_total 45756
telemt_handshake_timeouts_total 255729
telemt_upstream_connect_attempt_total 49492
telemt_upstream_connect_success_total 49471
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11025
telemt_me_reconnect_attempts_total 44232
telemt_me_reconnect_success_total 38239
telemt_me_reader_eof_total 40615
telemt_me_idle_close_by_peer_total 40614
telemt_me_route_drop_no_conn_total 1326759
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3230473
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10347
telemt_desync_full_logged_total 3519
telemt_desync_suppressed_total 6828
telemt_desync_frames_bucket_total{bucket="1_2"} 1872
telemt_desync_frames_bucket_total{bucket="3_10"} 3743
telemt_desync_frames_bucket_total{bucket="gt_10"} 4732
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38806
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38198
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 567
telemt_user_connections_total{user="hello"} 3229612
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 54681065080 (50.93 GB)
telemt_user_octets_to_client{user="hello"} 1157560329153 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 219038.1 (60h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2547314
telemt_connections_bad_total 23423
telemt_handshake_timeouts_total 323009
telemt_upstream_connect_attempt_total 67819
telemt_upstream_connect_success_total 65314
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67545
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20754
telemt_me_reconnect_attempts_total 59034
telemt_me_reconnect_success_total 47376
telemt_me_reader_eof_total 50762
telemt_me_idle_close_by_peer_total 50754
telemt_me_route_drop_no_conn_total 849214
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1994250
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4049
telemt_desync_full_logged_total 1325
telemt_desync_suppressed_total 2724
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1654
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48152
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47352
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 776
telemt_user_connections_total{user="hello"} 2000463
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 29787633107 (27.74 GB)
telemt_user_octets_to_client{user="hello"} 720278701446 (670.81 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88471.6 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993964
telemt_connections_bad_total 16756
telemt_handshake_timeouts_total 13029
telemt_upstream_connect_attempt_total 22159
telemt_upstream_connect_success_total 21565
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 22159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_keepalive_timeout_total 1700
telemt_me_reconnect_attempts_total 75328
telemt_me_reconnect_success_total 17139
telemt_me_reader_eof_total 19367
telemt_me_idle_close_by_peer_total 19366
telemt_me_route_drop_no_conn_total 385187
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920074
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2493
telemt_desync_full_logged_total 776
telemt_desync_suppressed_total 1717
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 727
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19115
telemt_me_refill_failed_total 1813
telemt_me_writer_restored_same_endpoint_total 17134
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1976
telemt_user_connections_total{user="hello"} 920013
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 16456212088 (15.33 GB)
telemt_user_octets_to_client{user="hello"} 308383082252 (287.20 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 105
```